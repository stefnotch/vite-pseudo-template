# Contributing Guide

Welcome, interested person! Contributions are welcome. If you're ever unsure, feel free to open an issue.

Preferably, features are developed in another branch or fork. After the feature is ready, a pull request to the master branch should be opened.

## Prerequisites

- [Node 16 or greater](https://nodejs.org/en/). Don't install Chocolatey.
- A code editor (see below)

## Setup

1. Fork the repository
2. Clone your fork
3. `npm install`
4. `npm run dev`

## Recommended Tooling

I recommend using [Visual Studio Code](https://code.visualstudio.com/) with

- [Prettier Extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) to format your files
- Settings &rarr; Format On Save &rarr; Enable (`"editor.formatOnSave": true,`)
  - Makes sure that autosave is either off or set to something that works properly
- [Volar Extension](https://marketplace.visualstudio.com/items?itemName=Vue.volar) for Vue.js
- [Typescript Vue Plugin](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) for Vue.js. Take-over mode is *not* recommended, so just get this plugin.
- [(optional)Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) to get inline error messages
- [(optional)npm Extension](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
- [(optional)TODO Highlight Extension](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [(optional)i18n Ally](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally) for translating and internationalizing code
- 
I also totally recommend using a decent browser such as Firefox or a Chromium browser with

- [Vue Devtools](https://devtools.vuejs.org/) to get top-notch debugging support

## Used Libraries

The most important ones are

- [Typescript](https://www.typescriptlang.org/) - Typesafe Javascript
- [Vue 3](https://github.com/vuejs/vue-next/) - Vue 3 with [the composition API](https://vuejs.org/guide/extras/composition-api-faq.html#what-is-composition-api)

We are also using

- [Vite](https://github.com/vuejs/vite) - a speedy Vue.js framework

## Code Structure

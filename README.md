# vuehelloword

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup
```sh
npm init --y (instan installer)
```
```sh
npm install
```
```sh
npm install <name-packed>
```
## Install Tailwind 
```sh
npm install vue-tailwind --save
```
## Configure Vue to use vue-tailwind
```sh
import Vue from 'vue'
import VueTailwind from 'vue-tailwind'

const components = {
  //...
}

Vue.use(VueTailwind, components)
```

### Compile and Hot-Reload for Development

```sh
npm run serve 'or' npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

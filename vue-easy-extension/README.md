# Create Chrome Extension Using Vue The Easiest Way


# Preparing the latest Node LTS

Useful NVM commands: https://gist.github.com/iotspace/f830c353ba0051627d161c7f26b67e8f

```bash
# list remove available versions of node
$ nvm ls-remote

# install specific version of node
$ nvm install 20.18.0

# set default version of node
$ nvm alias default 20.18.0

# switch version of node
$ nvm use 20.18.0

# list locally installed versions of node
$ nvm list
$ nvm ls

# check node version
$ node -v || node --version
v20.18.0

# check npm version
$ npm -v || npm --version
10.8.2
```

# Create new Vue project

```
$ cd chrome-extension-practices
$ npm init vue@latest
Need to install the following packages:
create-vue@3.11.2
Ok to proceed? (y)

> npx
> create-vue


Vue.js - The Progressive JavaScript Framework

RangeError: Incorrect locale information provided

✔ Project name: … vue-easy-extension
✔ Add TypeScript? … No / Yes
✔ Add JSX Support? … No / Yes
✔ Add Vue Router for Single Page Application development? … No / Yes
✔ Add Pinia for state management? … No / Yes
✔ Add Vitest for Unit Testing? … No / Yes
✔ Add an End-to-End Testing Solution? › No
✔ Add ESLint for code quality? … No / Yes
? Add Vue DevTools 7 extension for debugging? (experimental) › No / Yes

Scaffolding project in ~/chrome-extension-practices/vue-easy-extension...

Done. Now run:

  cd vue-easy-extension
  npm install
  npm run dev
```

# vue-easy-extension

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

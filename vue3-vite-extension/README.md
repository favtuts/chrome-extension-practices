# How to Create a Chrome Extension Using Vue 3?

# Step 1: Setting Up the Project

First, create a Vue 3 project using Vite by running the following command:
```bash
$ npm create vite@latest
Need to install the following packages:
create-vite@5.5.4
Ok to proceed? (y) y


> npx
> create-vite

✔ Project name: … vue3-vite-extension
✔ Select a framework: › Vue
✔ Select a variant: › TypeScript

Scaffolding project in /home/tvt/rewardstyle/chrome-extensions/chrome-extension-practices/vue3-vite-extension...

Done. Now run:

  cd vue3-vite-extension
  npm install
  npm run dev
```

Install the necessary dependencies:
```bash
$ cd vue3-vite-extension
$ npm install
```

Then, run the following command to spin up the server at http://localhost:5173/.
```bash
$ npm run dev
```

Now, install Ant Design and the CRXJS Vite Plugin:
```bash
$ npm install @crxjs/vite-plugin@beta -D
$ npm install ant-design-vue
```

# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).

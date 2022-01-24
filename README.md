# ViteJs + TypeScript + Webflow = ❤️

This is a basic setup with [ViteJs](https://vitejs.dev/) and [Typescript](https://www.typescriptlang.org/) that you can use for your Webflow website.
`jQuery` is already installed and declared as an external dependency.

I'm using [Netlify](https://www.netlify.com/) to build and host my code because it's easy to use, free, and has serverless functions out of the box. Feel free to use your favorite CDN.

## Live demo

You can find a simple example of a Webflow site using this setup [here](https://vite-typescript.webflow.io/). The code is hosted on Netlify [here](https://vite-typescript-webflow.netlify.app/main.js). If you want to see the Webflow preview, it's [here](https://preview.webflow.com/preview/vite-typescript?utm_medium=preview_link&utm_source=designer&utm_content=vite-typescript&preview=20fd1e1f69661819ee0812a9740cbdd3&workflow=preview) 👍

<br />

## How to use with Webflow

### 🇫🇷 French
The doc is [here](https://github.com/armandsalle/vite-typescript-webflow/blob/main/HowToUse_TS_FR.md) 

### 🇬🇧 English
The doc is [here](https://github.com/armandsalle/vite-typescript-webflow/blob/main/HowToUse_TS_EN.md) 

<br />

## Building and running on localhost

This project is using `yarn`.

First, install dependencies:

```sh
yarn
```

To launch a local dev server:

```sh
yarn dev
```

To create a production build:

```sh
yarn build
```

To clean the local `/dist` folder:

```sh
yarn clean
```

To lint the code with ESLint and Prettier:

```sh
yarn lint:fix
```

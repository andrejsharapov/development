# Development

## Content

- [Gulp](#gulp)
- [Nuxt](#nuxt)
- [Vite](#vite)
- [Vue CLI](#vue-cli)
- [VuePress](#vuepress)

## Gulp

### Installation

```shell
npm install --global gulp-cli
```

### Creating

```shell
npx mkdirp gulp-project && cd gulp-project && npm init && npm install --save-dev gulp
```

[More info][gulp]

## Nuxt

### Creating

```bash
yarn create nuxt-app nuxt-project
# or
npx create-nuxt-app nuxt-project
# or
npm init nuxt-app nuxt-project
```

### Running

```shell
cd nuxt-project && yarn dev
# or
cd nuxt-project && npm run dev
```

#### Path with Yarn

```bash
yarn create nuxt-app nuxt-project && cd nuxt-project && yarn dev
```

[More info][nuxt]

## Vite

### Creating

```shell
npm init @vitejs/app vite-project
# or
yarn create @vitejs/app vite-project
```

### Path Vite + Vue 3 with Yarn

```bash
yarn create @vitejs/app vite-project && cd vite-project && yarn install && yarn dev
```

[More info][vite]

## Vue CLI

### Installation

```bash
npm install -g @vue/cli
# or
yarn global add @vue/cli
```

### Upgrading

```bash
npm update -g @vue/cli
# or
yarn global upgrade --latest @vue/cli
```

### Create project

```shell
vue create vue-cli-project
```

#### Path with Yarn

```shell
vue create vue-cli-project && cd vue-cli-project && yarn serve
```

[More info][vue-cli]

## VuePress

### Creating

```shell
yarn create vuepress-project
# or
npx create-vuepress-site vuepress-project
```

#### Path with Yarn

```shell
yarn create vuepress-project && cd vuepress-project/docs/ && yarn install && yarn dev
```

[More info][vuepress]

<p align="right"><a href="#content">To top</a></p>

[gulp]: https://gulpjs.com/docs/en/getting-started/quick-start
[nuxt]: https://ru.nuxtjs.org/docs/2.x/get-started/installation
[vite]: https://vitejs.dev/guide/#scaffolding-your-first-vite-project
[vue-cli]: https://cli.vuejs.org/guide/installation.html
[vuepress]: https://vuepress.vuejs.org/guide/getting-started.html#quick-start

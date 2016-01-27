# NYPL Labs Boilerplate - Webpack + React

## Install

```shell
npm install
```
## Develop

```shell
npm start
```

This will run a development server on [http://localhost:3000](http://localhost:3000).

```shell
npm run lint
```
It is recommended that you add an [ESLint](http://eslint.org/) plugin to your preferred code editor, but you can also use this command.

## Build

```shell
npm run build
```

## Deploy

Runs build script, writes contents of `dist` directory to `gh-pages` branch, and pushes to GitHub, using [git-directory-deploy](https://github.com/lukekarrys/git-directory-deploy):

```shell
npm run deploy
```

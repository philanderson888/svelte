# getting started

## contents
- [getting started](#getting-started)
  - [contents](#contents)
  - [installing](#installing)
  - [build](#build)
  - [publishing](#publishing)
  - [getting started using `vite`](#getting-started-using-vite)

## installing

```js
npm create vite@latest hello-world-01 -- --template svelte
// choose svelte svelte-ts
cd hello-world-01
yarn install
yarn run dev
```

## build

to build only we run

```
yarn run build
```

which puts the output files in the `dist` folder

## publishing

deploy to `netlify` via `github` repository

build command is 

```js
npm run build
```

base directory is

```
/projects/hello-world-01
```

publish directory is

```
/projects/hello-world-01/dist
```

site is deployed to https://svelte-hello-world-01.netlify.app/


## getting started using `vite`

```js
npm init vite 
cd ...
npm install 
npm run dev
```

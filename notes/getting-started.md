# getting started

## contents
- [getting started](#getting-started)
  - [contents](#contents)
  - [installing](#installing)
  - [publishing](#publishing)

## installing

```js
npm create vite@latest hello-world-01 -- --template svelte
// choose svelte svelte-ts
cd hello-world-01
npm install
npm run dev
```

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

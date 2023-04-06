# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

```bash
npm create svelte@latest svelte-04
```

## Install

```bash
npm install
```

## run

```bash
npm run dev
# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

```bash
# run with no preview
npm run build
# run with preview
npm run preview
```

## deploying to netlify

must add `netlify.toml` in project root

```yaml
[build]
  command = "npm run build"
  publish = ".svelte-kit/output/client"
```

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
>
> so installing
>
> 
```bash
npm install -D @sveltejs/adapter-netlify
```



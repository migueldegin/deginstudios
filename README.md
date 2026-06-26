# Degin Studios

Static Astro website for Degin Studios, built for GitHub Pages.

## Development

```sh
npm install
npm run dev
```

The dev command uses Astro background mode. Manage it with:

```sh
npm run dev:status
npm run dev:logs
npm run dev:stop
```

## Build

```sh
npm run build
```

## Deploy

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds the site and
deploys `dist` to GitHub Pages on pushes to `main`.

For the repository `migueldegin/deginstudios`, the Astro config uses:

```js
site: 'https://migueldegin.github.io',
base: '/deginstudios'
```

If you switch to a custom domain, update `astro.config.mjs` accordingly.

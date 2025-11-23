# Template Nuxt 4

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install dependencies:

```bash
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
bun run dev
```

## Production

Build the application for production:

```bash
bun run build
```

Locally preview production build:

```bash
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

## Setup on Render.com

Create a new *Web Service*.

Set Language to *Node*.

Set *Build Command* to:

```bash
bun install --frozen-lockfile && bun run build
```

Set *Start Command* to:

```bash
bun .output/server/index.mjs
```

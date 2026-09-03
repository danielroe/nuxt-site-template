# Nuxt Site Template

A starting point for a Nuxt 4 site, with linting, type checking, unit/component tests (Vitest) and browser tests (Playwright) already configured.

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

```bash
pnpm install
```

## Development

Start the development server on `http://localhost:3000`:

```bash
pnpm dev
```

## Testing

```bash
pnpm lint          # eslint
pnpm test:types    # vue-tsc
pnpm test:unit     # vitest, node environment
pnpm test:nuxt     # vitest, nuxt environment
pnpm test:browser  # playwright
```

Browser snapshots are platform-specific, so update them inside the Playwright container:

```bash
pnpm test:browser:update
```

## Production

```bash
pnpm build     # build for production
pnpm preview   # preview the production build locally
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

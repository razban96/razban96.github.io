# razban96.github.io

This repository contains Răzvan Chiurtu's personal GitHub Pages site. It is a static
[Astro](https://astro.build/) site deployed from `main` to
<https://razban96.github.io>.

## Project conventions

- The home page and profile content live in `src/pages/index.astro`.
- Static assets belong in `public/` and are referenced with root-relative URLs.
- Keep external profile links and contact details in the page's profile/link data.
- Do not commit secrets or local environment files.
- Preserve accessible link names, image alt text, keyboard focus states, and responsive behavior.

## Development

Install dependencies with:

```sh
npm ci
```

Start the dev server in the background:

```sh
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

Before submitting changes, run:

```sh
npm run build
```

The build output is generated in `dist/` and must not be committed. Changes pushed
to `main` are deployed automatically by `.github/workflows/deploy.yml`; pull
requests should be checked with the local production build first.

For Astro-specific questions, consult the
[Astro documentation](https://docs.astro.build/).

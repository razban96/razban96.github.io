# razban96.github.io

Personal portfolio and contact page for **Răzvan Chiurtu**, built with Astro and
hosted on GitHub Pages.

**Live site:** <https://razban96.github.io>

## Stack

- [Astro](https://astro.build/)
- Node.js 22 or newer
- GitHub Pages with GitHub Actions

## Local development

Install the locked dependency versions and start Astro:

```sh
npm ci
npm run dev
```

The development site is available at <http://localhost:4321>.

## Production build

Create and preview the static production output:

```sh
npm run build
npm run preview
```

The generated `dist/` directory is ignored by Git.

## Updating the page

The profile, social links, email address, and page styles are defined in
`src/pages/index.astro`. Add or replace images in `public/`; they can be
referenced from the page with paths such as `/profile-picture.jpg`.

## Deployment

Every push to `main` runs `.github/workflows/deploy.yml`, builds the site, and
publishes it to GitHub Pages. The workflow can also be started manually from the
repository's **Actions** tab.

For the first deployment, enable **Settings → Pages → Source: GitHub Actions**
in the repository. No personal access token is required; the workflow uses the
GitHub Pages deployment permissions.

## Useful commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the static site |
| `npm run preview` | Preview the production build |
| `npm run astro -- --help` | Show Astro CLI help |

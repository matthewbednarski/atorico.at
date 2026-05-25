# Atorico static site

Static website for [atorico.at](https://atorico.at), built with Astro.

## Goals

- Replace the Ghost blog as the main company/product site
- Give full layout control for EarlyBird and service pages
- Keep posts available for later migration
- Support GitHub Pages deployment

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deployment

The repository includes a GitHub Actions workflow for GitHub Pages:

```txt
.github/workflows/deploy.yml
```

After pushing to `main`, enable GitHub Pages with **GitHub Actions** as the source.

## Migration checklist

- [ ] Create the GitHub repo, for example `matthewbednarski/atorico-site`
- [ ] Push this starter
- [ ] Enable GitHub Pages
- [ ] Add production images/screenshots to `public/images`
- [ ] Replace placeholder post list with migrated Ghost posts
- [ ] Confirm Contact and Calendly links
- [ ] Finalize privacy policy analytics section
- [ ] Configure custom domain `atorico.at`
- [ ] Add redirects from old Ghost URLs if needed

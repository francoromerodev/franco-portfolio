# Franco Romero — Portfolio

Personal portfolio of Franco Romero, a software engineer working on full-stack platforms, payment systems, and cross-platform mobile apps.

**Live site:** https://francoromero.vercel.app

## What's on the site

- **Selected work.** Write-ups of three projects: a subscription streaming app on Supabase and Mercado Pago, an affiliate marketing platform rebuilt on PostgreSQL and Stripe Connect, and a Flutter campsite discovery app.
- **About.** How I approach data integrity and production work.
- **Skills and contact.** The tools I use and how to reach me.

## Stack

The site is plain HTML, CSS, and JavaScript, built with [Vite](https://vite.dev) and deployed on Vercel. It has no framework and no runtime dependencies, because a static one-page site doesn't need them.

- Semantic HTML with a skip link and Open Graph / Twitter card metadata.
- A single stylesheet with responsive layouts.
- About 20 lines of JavaScript that reveal project cards on scroll with `IntersectionObserver`. Users who prefer reduced motion get no animation, and cards show immediately in browsers without `IntersectionObserver`.

## Running it locally

Requires Node.js 18 or later.

```bash
npm install
npm run dev       # start the dev server on http://localhost:5173
npm run build     # build the production site into dist/
npm run preview   # serve the production build locally
```

## Project structure

```
index.html      # all page content and metadata
styles.css      # layout, typography, and theming
main.js         # scroll-reveal behaviour
public/         # favicon and social preview images
```

## Contact

[LinkedIn](https://www.linkedin.com/in/francoromerodev/) · [Email](mailto:francoromerocba98@gmail.com)

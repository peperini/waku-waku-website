# Waku Waku

Website for Waku Waku, an independent creative agency bringing brand,
design, and technology together. Intentionally small and full of ideas,
the studio creates distinctive identities and digital experiences that
help brands connect with people.

## Tech stack

- Eleventy for static site generation
- Pug for page templates
- Sass for styling
- JavaScript and GSAP for interactions and animation
- Vite for asset processing and bundling

## Getting started

With Node.js and npm installed, run:

```sh
npm ci
npm run dev
```

Open the local URL printed in the terminal.

## Commands

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server with incremental builds. |
| `npm run build` | Generate the production site in `_site/`. |
| `npm run clean` | Remove the generated `_site/` directory. |

## Project structure

```text
public/              Static assets
src/
  app/               JavaScript and interactions
  styles/            Sass stylesheets
  views/             Pug pages and templates
    _data/           Shared template data
    _includes/       Reusable template partials
eleventy.config.js   Eleventy and Vite configuration
_site/               Generated site output (ignored by Git)
```

# The Story Speaks

Emmy-winning film and video production by Lance Murphey, based in Boulder, Colorado.

Built with [Astro](https://astro.build), deployed on [Cloudflare Pages](https://pages.cloudflare.com).

## Local development

```bash
npm install
npm run dev
```

Open `http://localhost:4321` to see the site.

## Project structure

```
src/
├── components/    Reusable section components (Hero, IntroSection, etc.)
├── layouts/       Page wrappers (BaseLayout)
├── pages/         Route-based pages (index = homepage)
└── styles/        Global CSS and design tokens
public/            Static assets served as-is (images, favicon)
```

## Build

```bash
npm run build
```

Output is generated to the `dist/` directory and served by Cloudflare Pages.

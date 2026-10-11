# MobiPay Admin Dashboard

**Live link:** _add your Netlify / Vercel / GitHub Pages link here_

A responsive admin dashboard for a fictional mobile-money app, built with the Tailwind CSS v4 CLI. No JavaScript files: the mobile sidebar opens with a CSS-only checkbox (`peer`).

## Run it

```bash
npm install
npm run dev      # rebuilds dist/output.css while you edit
npm run build    # minified dist/output.css
```

Then open `index.html` in the browser (or use the Live Server extension).

## What is inside

- Sidebar (5 links with icons), hidden on mobile and always visible from `lg:`
- Top bar with title, search and avatar
- 4 stat cards: 1 column, 2 at `md:`, 4 at `xl:`
- Transactions table with status badges, scrolls sideways on small screens
- Recent activity and Top services panels
- "Add new user" form
- Theme in `src/style.css`: `brand` color palette and Poppins font
- Reusable classes with `@apply`: `.card`, `.btn-primary`, `.btn-secondary`, `.badge`, `.input`, `.nav-link`

## Deploy

- **Netlify:** build command `npm run build`, publish directory `.`
- **GitHub Pages:** keep `dist/output.css` committed and publish from the main branch root.

## Checked at

375px, 768px, 1024px and 1440px.
<<<<<<< HEAD
# gthuo-github.github.io
My Professional Portfolio
=======
# Portfolio — Next.js + TypeScript

A one-page data/dev portfolio site styled after a dark theme with a
cyan → violet → magenta gradient accent, built with Next.js 14 (App Router),
TypeScript, and Tailwind CSS.

## Getting started

```bash
npm install
npm run dev
```

Open http://localhost:3000 to view it.

## Customize

- **Name & bio** — edit `components/Hero.tsx` and `components/About.tsx`.
- **Avatar** — replace the initials placeholder in `Hero.tsx` with your own
  photo (drop an image in `/public` and swap in an `<Image />` component).
- **Skills** — edit the `GROUPS` array in `components/Skills.tsx`.
- **Projects** — edit the `PROJECTS` array in `components/Projects.tsx`. Each
  project can use a `bar` or `line` chart thumbnail, or you can swap in a real
  screenshot.
- **Resume** — drop your PDF in `/public/resume.pdf` (the button in `Hero.tsx`
  already links to it).
- **Contact links** — edit `SOCIALS` in `components/Contact.tsx`.
- **Colors** — all tokens live in `tailwind.config.ts` (`cyan`, `violet`,
  `magenta`, `ink`, `panel`, `fog`, `muted`) and in `app/globals.css`.

## Build a static export

This project is configured with `output: "export"` in `next.config.js`, so
`npm run build` produces a static site in `/out` that can be deployed to
GitHub Pages, Netlify, Vercel, or any static host.

```bash
npm run build
```
>>>>>>> 11bdf56 (Initial Commit to My Portfolio)

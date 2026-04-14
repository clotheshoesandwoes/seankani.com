# CLAUDE.md — seankani.com

**Project:** Portfolio website for Sean Kani  
**URL:** seankani.com  
**Stack:** Astro (static site)  
**Hosting:** TBD (likely Vercel)

---

## Project Structure

```
seankani.com/
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── public/
│   └── favicon.svg
└── src/
    ├── components/
    ├── layouts/
    │   └── Base.astro
    ├── pages/
    │   └── index.astro
    └── styles/
```

---

## Commands

```bash
npm run dev       # Dev server
npm run build     # Production build
npm run preview   # Preview production build
```

---

## Rules

- This is a public-facing portfolio site — polish and simplicity matter
- Dark theme, minimal, clean
- Mobile-first responsive
- Keep it fast — no unnecessary JS, no heavy frameworks
- Show projects with links to live demos / repos

---

## Git

- Commit messages: concise, no fluff
- No `Co-Authored-By` trailers

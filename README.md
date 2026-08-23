# Selected Work — Index

> The portfolio index for 90 independently built and deployed web applications.

**[Live demo](https://su-slopmachine.vercel.app)**

Each of the 90 apps in this series lives in its own repository with its own Vercel deployment, which leaves the problem of where they are collectively presented. This is that page: a single static HTML document, laid out as an editorial catalogue rather than a card grid. Every entry carries its product name, description, and category in four languages, so switching language re-renders the entries themselves and not just the surrounding chrome.

## Features

- Catalogue of 90 apps, each row linking to both the live deployment and its public source
- Live client-side search across names, titles, descriptions and repo slugs — press `/` to focus, `Esc` to clear
- Category filters: AI, developer tools, marketing, utilities, computer vision, interactive
- Four-language interface (English, Spanish, Portuguese, French), auto-detected from `navigator.language` and remembered in `localStorage`
- Light and dark themes that follow the system preference, with a manual toggle that persists
- Keyboard accessible throughout, with skip link, visible focus rings, and `prefers-reduced-motion` support

## Stack

- Vite (static build, no UI framework)
- Vanilla JavaScript — the app dataset is a hardcoded array in `index.html`
- Fraunces and IBM Plex Sans/Mono via Google Fonts
- Deployed on Vercel

## Running locally

```bash
npm install
npm run dev
```

No environment variables are required — the page is fully static.

---

Part of a series of 90 small web apps. [Browse them all](https://su-slopmachine.vercel.app).

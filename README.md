# The Slop Machine

> A single-page index of every app produced by an automated startup-idea loop.

**[Live demo](https://su-slopmachine.vercel.app)**

An autonomous agent loop keeps generating, building, and deploying small web apps, which leaves the problem of where they all live. The Slop Machine is the directory: one static HTML page holding a hardcoded array of 90 entries, each rendered as a card with its number, trademarked product name, one-line description, category tag, repo name, and a link to the live deployment. Every entry carries its name, title, and description in four languages, so switching language re-renders the whole grid rather than just the chrome.

## Features

- Grid of 90 deployed apps, each card linking straight to its live Vercel URL
- Category filter bar — All, AI-Powered, Dev Tools, Marketing, Fun & Viral, Utilities, Vision AI — with per-tag accent colors
- Full four-language UI (English, Spanish, Portuguese, French) covering headings, filters, tags, and every app description
- Language auto-detected from `navigator.language` and remembered in `localStorage`
- Dark theme with a header stat block (app count, $0 budget) and a manifesto footer
- Responsive card grid that collapses to a single column on mobile

## Stack

- Vite (static build, no framework)
- Vanilla JavaScript in a single `index.html` — zero runtime dependencies
- Hand-written CSS with custom properties for theming

## Running locally

```bash
npm install
npm run dev
```

---

Part of a series of 91 small web apps. [Browse them all](https://su-slopmachine.vercel.app).

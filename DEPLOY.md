# Deploying the author website to Vercel

This is a static site (just `index.html` + `images/`). No build step needed.

## Current live setup
- GitHub repository: `eyeinthesky6/preditorium-prophecy`
- Vercel project: `sixideas/preditorium-prophecy`
- Production domain: `https://preditorium.com`

Changes pushed to the GitHub `main` branch are intended to deploy through the
connected Vercel project.

## Manual Vercel CLI deploy
Use this only if you need to deploy outside the GitHub flow:

```bash
vercel --prod --scope sixideas
```

## After it's live
- Copy the live URL — that's the "author website" link for the Goodreads
  Author Program application. It already shows **thakur.jai@gmail.com** in the
  Contact section and footer, which is what Goodreads checks.

## What to update later
- When the **ebook** goes live, add its buy link in the "Get Your Copy" section.
- Swap in an author photo if you want one (drop it in `images/` and add an
  `<img>` in the Author section).

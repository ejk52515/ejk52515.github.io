# Portfolio — GitHub Pages deployment

## Files

- `index.html` — homepage (hero, about teaser, featured projects, cert roadmap, contact)
- `projects.html` — full project writeups (problem / build / what it demonstrates)
- `bio.html` — career story + timeline + skills
- `styles.css` — shared design system for all three pages
- `resume.pdf` — YOU add this (linked from index and bio)

## One-time setup (~5 minutes)

1. Create a new **public** repo on GitHub named exactly:
   `yourusername.github.io`

2. Clone it, drop in these files, push:

   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   # copy index.html, projects.html, bio.html, styles.css, resume.pdf here
   git add .
   git commit -m "Initial portfolio"
   git push
   ```

3. Live at `https://yourusername.github.io` within a minute or two.
   (If not: repo Settings → Pages → Source = "Deploy from a branch" / main.)

## Before publishing — fill in the TODOs

Search **all three HTML files** for `TODO`:

| # | What | Where |
|---|------|-------|
| 1 | Your full name | title tags, footers, nav brand |
| 2 | GitHub repo/profile URLs | project writeups + contact buttons |
| 3 | LinkedIn URL | contact sections |
| 4 | Email address | contact sections (mailto:) |
| 5 | resume.pdf | repo root |

Also review the bio page — the timeline uses role titles without employer
names or dates. Add company names/years if you want them public; recruiters
generally like seeing them, but it's your call on a public site.

## Updating later

Edit → commit → push. That's the pipeline.

## Optional upgrades

- Custom domain: Settings → Pages → add domain, set DNS at registrar.
  GitHub provides free HTTPS.
- Per-project deep dives: add pages like `projects/hardened-dc.html`
  with diagrams and code snippets, link from the writeups.

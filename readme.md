# Pranav Pandey: Portfolio

Static site (HTML/CSS/JS, no build step, no dependencies).

## Run locally
Open `index.html` in a browser, or: `npx serve .` (or `python3 -m http.server`).

## Customize
Edit the `CONFIG` block at the top of the `<script>` in `index.html`:
- `technovaUrl`: set your TechNova link to show the "Visit TechNova" button.
- `pinned` / `hidden`: control which GitHub repos appear first or are hidden.

## Deploy
**GitHub Pages:** push these files to a repo (e.g. `git-pranav-09.github.io`), then Settings > Pages > Deploy from branch `main` / root.
**Vercel:** import the repo, framework preset "Other", no build command, output directory `.`.

## Before sharing
Add `og:image` (absolute URL) and `og:url` meta tags once you have a domain.

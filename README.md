# Mentora AI — Company Website

A modern, single-page marketing website for Mentora AI, an AI integration
consulting and mentorship company.

## What's inside

- `index.html` — the entire site (HTML, CSS, and JavaScript in one
  self-contained file, no build step and no external dependencies).

## Sections

- **Hero** — headline, call to action, and animated company stats
- **Services** — six service offerings (AI strategy, workflow integration,
  building with AI, training & mentorship, governance, ongoing partnership)
- **How we work** — the four-step engagement process
- **Mentors** — the team
- **Why us** — differentiators
- **Testimonials, FAQ, and Contact**

## Running locally

Just open `index.html` in any browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

The site is fully static, so it can be hosted anywhere — GitHub Pages,
Netlify, Vercel, or any web server. For GitHub Pages: Settings → Pages →
deploy from the branch root.

## Customizing

- **Company name / logo**: search for "Mentora" in `index.html`.
- **Contact email**: search for `hello@mentora.ai`.
- **Colors**: edit the CSS variables at the top of the `<style>` block
  (`--accent`, `--grad`, etc.).
- **Mentors, testimonials, stats**: edit the corresponding sections —
  the current names and numbers are placeholders to replace with your
  real team and figures.

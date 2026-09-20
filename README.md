# BNEF Forum Abu Dhabi 2026 — Agenda Page

A static, self-contained HTML page for the BloombergNEF Forum Abu Dhabi 2026 agenda, built as a standalone redesign concept for internal review.

**This is a design concept, not the live BNEF site.** It reuses the real site's navigation structure and footer links (pointing back to the real about.bnef.com pages), with the hero, agenda timeline, speakers grid and venue section rebuilt in the [BNEF Events Page](https://github.com/market-partner-sites/bnef-events-page) design system. The "All events" link and logo point to that companion concept's live page.

Agenda content (sessions, times, speakers, descriptions) and venue details are taken from the real [forum agenda page](https://about.bnef.com/events/forum-agenda-abudhabi-2026/). The "Register Interest" button links out to that real page rather than reproducing its form.

This page is independent of the `bnef-events-page` repo — it carries its own copy of the shared assets (logo, favicons) so it can be hosted on its own.

## Viewing it

Open `forum-agenda-abudhabi-2026.html` directly in a browser, or, once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), view it at:

```
https://<your-github-username-or-org>.github.io/<repo-name>/forum-agenda-abudhabi-2026.html
```

## Notes

- Typeface is set to `Avenir Next` / `Avenir` (Bloomberg's brand font), falling back to Poppins/Inter via Google Fonts for viewers who don't have Avenir installed locally.
- No build step — it's a single plain HTML file with inline CSS and vanilla JS, so it works as-is on GitHub Pages, Netlify, or any static host.

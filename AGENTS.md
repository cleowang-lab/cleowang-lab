# Website Content Conventions

- Keep the site palette consistent. Use the shared `ntu2` theme: blue `#003d7c` for primary accents and links, `#002f5f` for hover states, and the existing light blues for dark mode. Do not introduce green accents or page-specific colour overrides.
- News articles use Inter for body text, metadata and subheadings, with Oswald for the main title. Maintain these styles in `assets/scss/template.scss`, rather than embedding styles in individual posts.
- Do not show an author biography/profile at the end of News articles. Keep the shared News cascade in `content/news/_index.md` so future posts inherit this setting.
- Keep Disqus comments disabled on News articles through the shared News cascade.

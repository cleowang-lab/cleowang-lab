# Website Content Conventions

- Keep the site palette consistent. Use the shared `ntu2` theme: blue `#003d7c` for primary accents and links, `#002f5f` for hover states, and the existing light blues for dark mode. Do not introduce green accents or page-specific colour overrides.
- News articles use Inter for body text, metadata and subheadings, with Oswald for the main title. Maintain these styles in `assets/scss/template.scss`, rather than embedding styles in individual posts.
- Do not show an author biography/profile at the end of News articles. Keep the shared News cascade in `content/news/_index.md` so future posts inherit this setting.
- Keep Disqus comments disabled on News articles through the shared News cascade.

# Repository And Publishing

- Use `/Users/chuchu/Projects/cleowang-lab` as the canonical source checkout. The OneDrive checkout is a legacy copy.
- Source repository: `cleowang-lab/cleowang-lab`, branch `main`.
- The live site at `https://www.chuchuwanglab.com/` is served by GitHub Pages from `cleowang-lab/cleowang-lab.github.io`, branch `main`. The Netlify configuration is not the active publishing path.
- Publishing requires both pushing the source changes and building the production Hugo site into a separate output directory, then committing and pushing the generated files to the GitHub Pages repository. Preserve its `CNAME` value `www.chuchuwanglab.com` and verify the live page after deployment.

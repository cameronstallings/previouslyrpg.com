# previouslyrpg.com

The public website: home, `/privacy/`, `/terms/`, the invite landing for
`/j/CODE` (served by `404.html`, which doubles as the not-found page), and the
Apple association file for universal links.

Plain HTML, no build step. `.nojekyll` makes GitHub Pages serve the
`.well-known` directory.

Published from the public repo `cameronstallings/previouslyrpg.com` on GitHub
Pages (its `main` branch is this directory). The source of truth is
`site/` in the private Previously repo; `node scripts/publish-site.mjs`
copies it over and pushes.

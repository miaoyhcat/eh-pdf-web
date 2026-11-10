# Manga → PDF & Reader — launcher

Static entry point on GitHub Pages. GitHub Pages is HTTPS-only and static, so it cannot host
the application itself (Python + `gallery-dl` + PDF pipeline). This page simply forwards to the
running instance.

The application repository is private; UI/docs of the public project live in the project repo.

- `index.html` — redirect + manual link
- `config.js` — kept for compatibility, unused by the launcher

If the tunnel URL changes, update it in `index.html` (two places).

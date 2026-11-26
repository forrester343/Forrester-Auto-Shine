# Forrester-Auto-Shine

Netlify publishes the static files in `site/`. The current `site/index.html` is a temporary holding page because the original website files are not in this repository.

To restore the original website, extract the original ZIP outside the repository and copy only its publish-ready files into `site/`, replacing the holding page. Check that the original `index.html` is directly inside `site/` and that the assets keep their relative paths. Commit those files rather than the ZIP, and keep `netlify.toml` at the repository root.

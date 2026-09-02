# Sortello Site (`sortello.bytesololabs.com`)

GitHub Pages website and deep link routing for **Sortello** by ByteSolo Labs.

## Structure

- `CNAME`: Configures custom domain `sortello.bytesololabs.com`.
- `.nojekyll`: Disables Jekyll processing on GitHub Pages.
- `index.html`: Apple-style responsive landing page with challenge link inspector.
- `icon.png` & `favicon.png`: High-res brand icons.
- `g/index.html`: Handles shared challenge deep links (`https://sortello.bytesololabs.com/g?g=<token>`).
- `privacy/index.html`: Privacy Policy for Sortello (`https://sortello.bytesololabs.com/privacy`).
- `terms/index.html`: Terms of Service for Sortello (`https://sortello.bytesololabs.com/terms`).

## Deployment

Deploy this folder to GitHub Pages under the `bytesololabs/sortello-site` repository (root `/` branch).
Ensure HTTPS enforcement is enabled in the GitHub Pages settings.

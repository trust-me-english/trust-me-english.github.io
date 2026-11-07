# trust-me-english-site

Public pages for Trust Me English, served by GitHub Pages:

- `privacy.html`: Privacy Policy (English, legally binding version).
- `privacy.ru.html`: Russian translation.
- `index.html`: a minimal landing page linking to them.

Plain HTML and one stylesheet, no build step.

## Before publishing

Replace every placeholder, shown highlighted on the page:

- `[FULL NAME]` / `[ИМЯ И ФАМИЛИЯ]`, `[BUSINESS NAME]` / `[НАЗВАНИЕ JDG]`, `[ADDRESS]` / `[АДРЕС]`, `[NIP]`: as in CEIDG.
- `[PRIVACY EMAIL]`: the project contact address (also in `mailto:` links).

Then remove the `placeholder` spans, so the text is no longer highlighted.

## Publishing on GitHub Pages

1. Create a public GitHub repository `trust-me-english-site` and push `main`.
2. Repository → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The policy is then at `https://<github-user>.github.io/trust-me-english-site/privacy.html`. This URL goes to App Store Connect, TikTok for Developers and Meta for Developers.
4. Optional: a custom domain (Settings → Pages → Custom domain), which keeps the URL stable if the hosting changes.

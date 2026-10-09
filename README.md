# Lasatho.github.io

Persönliche Portfolioseite auf Basis des [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)-Themes (Jekyll).

## Deployment

Build und Deploy laufen über GitHub Actions (`.github/workflows/pages-deploy.yml`),
nicht über den nativen „deploy from branch"-Build. In den Repo-Einstellungen muss
**Settings → Pages → Source = GitHub Actions** gesetzt sein. Jeder Push auf `main`
baut und veröffentlicht die Seite.

## Lokale Vorschau

Benötigt Ruby + Bundler:

    bundle install
    bundle exec jekyll serve

Öffnet <http://127.0.0.1:4000>.

## Struktur

- `_config.yml` – Seitenkonfiguration, Identität, Theme
- `index.html` – Startseite (Chirpy `home`-Layout)
- `_tabs/` – Navigationsseiten (`projects.md`, `about.md`)
- `_posts/` – Blog-/Writeup-Beiträge (optional)
- `_data/` – Kontakt- und Share-Optionen
- `_plugins/` – Build-Hooks

## Hinweis Lebenslauf

Der vollständige Lebenslauf liegt bewusst nicht im Repo/öffentlich. GitHub Pages
ist rein statisch und kann keine serverseitige Zugriffskontrolle; ein gated
Zugriff erfordert einen externen Dienst (Formular oder Cloudflare Access).

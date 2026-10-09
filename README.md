# Lasatho.github.io

Persönliche Portfolioseite (Jekyll, GitHub Pages).

## Lokale Vorschau
Benötigt Ruby + Bundler:

    bundle install
    bundle exec jekyll serve

Öffnet http://127.0.0.1:4000. GitHub Pages baut `main` automatisch, lokale
Vorschau ist optional.

## Struktur
- `_config.yml` – Seitenkonfiguration, Theme (minima), Navigation
- `index.md` – Startseite
- `projects.md`, `about.md` – Inhaltsseiten

## Hinweis Lebenslauf
Der vollständige Lebenslauf liegt bewusst nicht im Repo/öffentlich. GitHub Pages
ist rein statisch und kann keine serverseitige Zugriffskontrolle; ein gated
Zugriff erfordert einen externen Dienst (Formular oder Cloudflare Access).

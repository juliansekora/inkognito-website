# Inkognito – Website

Statische Landing-Page für die iOS-Party-App **Inkognito** (das Bluff-Mal-Spiel).

## Inhalt
- `index.html` – Landing-Page (zweisprachig DE/EN, Umschalter oben rechts)
- `privacy.html` – Datenschutzerklärung (Entwurf – Adresse ergänzen, rechtlich prüfen)
- `support.html` – Support/FAQ
- `favicon.svg` – Markenicon (zwinkernde Maske)

Kein Build-Schritt nötig – reines HTML/CSS/JS.

## Deployment (Vercel)
1. Auf [vercel.com](https://vercel.com) → **Add New… → Project** → dieses GitHub-Repo importieren.
2. Framework Preset: **Other** (statisch), Build Command leer, Output leer.
3. Deploy. Vercel baut bei jedem `git push` automatisch neu.

> Wichtig: Als **neues** Vercel-Projekt importieren – bestehende Projekte werden dabei nicht verändert.

## Lokal ansehen
Einfach `index.html` im Browser öffnen.

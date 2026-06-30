# drklass.de

Persönliche Website von Dr. med. Dietmar Klass — Facharzt für Gastroenterologie, Lüneburg.

## Stack

- **Landingpage** (`index.html`) — statisches HTML/CSS, kein Build-Tool
- **Texte** (`/texte/`) — Jekyll-Collection für Prosa und Kurzgeschichten

GitHub Pages baut Jekyll automatisch bei jedem Push.

## Struktur

```
index.html              — Landingpage (statisch, kein Front Matter)
impressum.html
datenschutz.html
_config.yml             — Jekyll-Konfiguration
_layouts/
  text.html             — Lese-Layout für einzelne Texte
  texte_index.html      — Übersichtsseite /texte/
assets/css/
  text.css              — Typografie-Styling für den Texte-Bereich
texte/
  index.html            — Einstieg /texte/
_texte/
  *.md                  — Einzelne Texte als Markdown
```

## Neuen Text veröffentlichen

Datei in `_texte/` anlegen:

```yaml
---
layout: text
title: "Titel der Geschichte"
date: 2026-01-01
genre: Kurzgeschichte
permalink: /texte/url-freundlicher-titel/
excerpt: "Erster Satz für die Übersicht."
# image: /assets/images/texte/bild.jpg   # optional
---

Text in Markdown...
```

`---` im Text erzeugt einen `· · ·`-Abschnittstrenner.

## Bildnachweise

Bannerfoto: [Philipp Deus](https://unsplash.com/de/@deuspix) auf [Unsplash](https://unsplash.com/de/fotos/braunes-und-weisses-betongebaude-tagsuber-0kYnrAyKHtM)

## Lizenz

© Dr. med. Dietmar Klass. Alle Rechte vorbehalten.

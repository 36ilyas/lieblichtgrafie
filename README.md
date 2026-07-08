# Lieblichtgrafie

Portfolio-Website für die Hochzeits- und Porträtfotografin **Chau Pham**.

Eine leichtgewichtige, animierte Single-Page-Site ohne Build-Schritt — reines HTML/CSS/JS.

## Struktur

```
.
├── index.html      # Komplette Seite (Markup, Styles, Skripte inline)
└── assets/         # Bilder
    ├── Chau.png
    ├── Hochzeit.png
    └── Solo.png
```

## Lokal ansehen

Öffne `index.html` direkt im Browser, oder starte einen kleinen Server:

```bash
python -m http.server 8000
# → http://localhost:8000
```

## Sektionen

- **Hero** — animierte Farb-Blobs, geschwungene Signatur-Linie
- **Über** — Porträt und Selbstvorstellung
- **Werke** — Galerie mit sechs Serien im Reveal-on-Scroll
- **Kontakt** — Formular mit sanfter Bestätigungsanimation

## Design-Tokens

Alle Farben und Typografie werden als CSS-Custom-Properties in `:root` gepflegt (`--paper`, `--terracotta`, `--petrol` …).

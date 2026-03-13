# isacgustafsson.se

Personlig portföljsida för Isac Gustafsson — systemutvecklare, arkitekt och grundare av C.I.L. Inventions.

## Teknikstack

Statisk single-page webbplats byggd med ren HTML/CSS/JavaScript. Inga ramverk eller byggsteg krävs.

- **HTML/CSS/JS** — allt i en självständig `index.html`
- **Bilder** — inbäddade som base64 data URLs (fungerar utan webbserver)
- **Kontaktformulär** — [Formspree](https://formspree.io) (form ID: `mlgpnkkj`)
- **Fonter** — Google Fonts (Inter + Playfair Display)

## Struktur

```
isacgustafsson.se/
├── index.html        # Huvudfil — hela sidan
├── images/           # Originalbilder (används vid lokal utveckling)
└── README.md
```

## Sektioner

- **Hero** — introduktion och profilbild
- **Projekt** — Maintplanner, Assalub Apps, Profilerna, Player Compass, m.fl.
- **Om mig** — citat från kollegor och samarbetspartners
- **Erfarenheter** — Webking/Magello, Himmelsby SPA, C.L. Seifert, McDonald's
- **Utbildning** — TUC Yrkeshögskola, Försvarsmakten (GMU)
- **Kontakt** — formulär via Formspree, sociala medier, Google Maps

## Lokal utveckling

Öppna `index.html` direkt i webbläsaren — inga beroenden att installera.

```bash
git clone https://github.com/Isaczzon/isacgustafsson.se.git
cd isacgustafsson.se
# Öppna index.html i webbläsaren
```

## Driftsättning

Sidan är planerad att självhosted på en egen Windows Server med IIS/Nginx, med DNS via one.com.

Se [deployment-dokumentation](#) för serverkonfiguration (kommer).

## Kontakt

**Isac Gustafsson**
- E-post: isacgust@gmail.com
- LinkedIn: [linkedin.com/in/isac-gustafsson-608b12141](https://linkedin.com/in/isac-gustafsson-608b12141)
- Plats: Mantorp, Sverige

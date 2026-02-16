# ALS Training App 🏥

Interaktive Lern-App für die **ALS (Advanced Life Support) NFS-Rezertifizierung** des Roten Kreuz Niederösterreich.

## Features

- **ABCDE-Schema** – Alle 5 Stufen mit Beurteilung & Maßnahmen (Sanitäter vs. NFS/NKI)
- **ALS-Algorithmus** – Step-by-step Reanimations-Algorithmus nach ERC 2021
- **CRM-Leitsätze** – 15 Leitsätze nach Rall & Gaba mit Erklärungen
- **Quiz** – 24 Prüfungsfragen (zufällig gemischt) mit sofortigem Feedback
- **Fallbeispiele** – 3 Szenarien zum interaktiven Durcharbeiten

## Quellen

- [ERC Guidelines 2021 (GRC)](https://www.grc-org.de/wissenschaft/leitlinien)
- [RKNÖ RDmed Behandlungsleitlinien](https://rdmed.n.roteskreuz.at/books)
- [InPASS CRM](https://inpass.de/de-de/crew-resource-management-crm/)

## Deployment

Die App ist eine einzelne `index.html`-Datei und kann direkt über **GitHub Pages** gehostet werden:

1. Repository Settings → Pages
2. Source: `main` Branch, `/ (root)`
3. Save → fertig!

## Technologie

- React 18 (via CDN)
- Vanilla CSS
- Keine Build-Tools nötig – funktioniert standalone

# Generic – Dummy-Template

Eine **firmenneutrale Vorlage** dieser One-Page-Website. Alle Inhalte sind Platzhalter
(Lorem Ipsum, graue Bild-Platzhalter, Logo-Platzhalter), sodass sich für jede beliebige
Firma in wenigen Schritten eine fertige Seite aufsetzen lässt.

## So passt du es an

1. **Logo:** `assets/logo-placeholder.svg` durch dein Logo ersetzen (oder im `index.html`
   die beiden `logo__img` / `footer-brand__img`-`src` anpassen).
2. **Bilder:** eigene Fotos in `assets/` legen und in `index.html` jedes
   `src="assets/placeholder.svg"` darauf umbiegen (Hero 1600×900, Leistungen/News 800×500,
   Referenzen 600×450, Über-uns 800×600).
3. **Texte:** Lorem-Ipsum-Texte im `index.html` durch eigene Inhalte ersetzen.
4. **Firmenname & Kontakt:** „Musterfirma GmbH", „Musterstraße 1", Telefon, E-Mail und
   Öffnungszeiten überall im `index.html` + Footer austauschen.
5. **Farben & Schriften:** zentral in `css/style.css` ganz oben unter `:root`
   (`--color-primary`, `--color-secondary`, `--color-accent`, `--font-heading` …).
6. **Hero-Slogan:** die Typewriter-Phrasen in `js/main.js` (Abschnitt 5) anpassen.
7. **Kontaktformular:** Versand-Endpoint in `js/main.js` (Abschnitt 10) einbauen.

## Lokal ansehen

```bash
cd generic
python3 -m http.server 8080
# http://127.0.0.1:8080
```

Kein Build-Schritt nötig – reines HTML/CSS/JS.

> Ein vollständig ausgefülltes Beispiel auf Basis dieses Templates liegt im
> Ordner [`../destill-tech/`](../destill-tech/).

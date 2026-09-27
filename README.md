# dentiq.cloud

Statische Onepage-Website für DentIQ (kein Framework, keine externen Anfragen).

- Quelltext der Seiten: `src/*.html`, Icons als Platzhalter `{{icon:name}}`
- Bauen: `python3 build.py` → erzeugt `index.html`, `impressum.html`, `datenschutz.html` im Hauptordner
- Hosting geplant: GitHub Pages mit eigener Domain (`CNAME` = dentiq.cloud)

Vor Veröffentlichung offen:
- Impressum und Datenschutz ausfüllen (Platzhalter in [eckigen Klammern])
- `assets/img/og-image.jpg` (1200 × 630) für Link-Vorschauen anlegen
- Offizielle App-Store- und Google-Play-Badges einsetzen
- PDF-Screenshot mit echter Beispielfirma (Logo, Firmendaten) neu aufnehmen

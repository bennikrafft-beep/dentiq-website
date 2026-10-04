# dent-app.de

Statische Onepage-Website für Dent-App (kein Framework, keine externen Anfragen).

- Quelltext der Seiten: `src/*.html`, Icons als Platzhalter `{{icon:name}}`
- Bauen: `python3 build.py` → erzeugt `index.html`, `impressum.html`, `datenschutz.html` im Hauptordner
- Hosting geplant: GitHub Pages mit eigener Domain (`CNAME` = dent-app.de; dentiq.cloud leitet über das Repo dentiq-redirect weiter)

Vor Veröffentlichung offen:
- Impressum und Datenschutz ausfüllen (Platzhalter in [eckigen Klammern])
- PDF-Screenshot mit echter Beispielfirma (Logo, Firmendaten) neu aufnehmen

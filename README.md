# dentiq.cloud

Statische Onepage-Website für DentIQ (kein Framework, keine externen Anfragen).

- Quelltext der Seiten: `src/*.html`, Icons als Platzhalter `{{icon:name}}`
- Bauen: `python3 build.py` → erzeugt `index.html`, `impressum.html`, `datenschutz.html` im Hauptordner
- Hosting geplant: GitHub Pages mit eigener Domain (`CNAME` = dentiq.cloud)

Vor Veröffentlichung offen:
- Impressum und Datenschutz ausfüllen (Platzhalter in [eckigen Klammern])
- Sobald die Android-App live ist: in `src/index.html` die beiden `<span class="soon">…</span>` durch den Google-Play-Badge ersetzen
  (`<a class="store" href="https://play.google.com/store/apps/details?id=com.dentiq.app"><img src="assets/badges/google-play-de.png" alt="Jetzt bei Google Play" width="134" height="52"></a>`)
  und im JSON-LD `operatingSystem` wieder um „Android“ ergänzen
- PDF-Screenshot mit echter Beispielfirma (Logo, Firmendaten) neu aufnehmen

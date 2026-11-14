# tbstat-portal

Passwortgeschütztes Statistikportal des Tuberkulose-Zentrums Hamburg zur TB-Surveillance 2017–2025 (verschlüsselte Single-File-HTML-Seiten, AES-256-GCM).

**Aktuelle Version: v1.0** (14.11.2026)

## Dateien

- `index.html`, `tbhhstat.html`, `tbhhmap.html`, `tbhhrki.html`, `tbhh2025.html`: dunkle Fassung
- `*_hell.html`: helle Fassung derselben Seiten
- Die öffentliche Kurzfassung ohne Passwort liegt im Repository `tbstat-dashboard`.

## Versionierung

- Schema `vHAUPT.NEBEN` wie im Repository `tbstat-dashboard`: Jede inhaltliche Änderung erhöht die Nebennummer (v1.0, v1.1, v1.2 …). Die Hauptnummer steigt nur bei grundlegendem Umbau.
- Jede Änderung erhält einen Eintrag im Changelog und eine Commit-Nachricht der Form `Portal vX.Y: Kurzbeschreibung`.
- Dunkle und helle Fassung werden immer gemeinsam geändert und tragen dieselbe Versionsnummer.

## Changelog

- v1.0 (14.11.2026): Versionierung eingeführt. Ausgangsstand mit den Seiten `index`, `tbhhstat`, `tbhhmap`, `tbhhrki` und `tbhh2025` in dunkler und heller Fassung.

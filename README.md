# Medikamenten-App – Version 3

Offline-fähige PWA mit täglicher, wöchentlicher, monatlicher und Intervall-Einnahme sowie **Medikamenten nach Bedarf**.

## iPhone testen
1. Den **Inhalt** dieses Ordners in das Stammverzeichnis deines bestehenden GitHub-Pages-Repositories hochladen. `index.html` muss direkt im Repository-Stamm liegen.
2. GitHub → Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Die bestehende GitHub-Pages-URL in Safari öffnen und zum Home-Bildschirm hinzufügen.
4. App online einmal vollständig laden, danach Flugmodus-Test durchführen.

## Änderungen in Version 3
- Frequenz **Nach Bedarf** ohne festen Wochentag und ohne Uhrzeit.
- Mehrere tatsächliche Einnahmen pro Tag einzeln erfassbar und einzeln entfernbar.
- Gesonderter Abschnitt auf dem Heute-Bildschirm, keine Bedarfsmedikamente im Soll-Zähler.
- iPhone-17-Pro-optimiertes responsives Layout mit Safe-Area-Unterstützung.
- Neues Tabletten-App-Icon.
- Vorhandene lokale Daten werden weiterhin mit dem bisherigen Speicherschlüssel gelesen.

## Wichtige Hinweise
- Die Anwendung ist **keine medizinische Dosierungsberatung**; bei Bedarfsmedikamenten werden keine Höchstdosen oder Mindestabstände geprüft.
- Browserdaten können verloren gehen. Regelmäßig JSON-Backup exportieren.
- iOS-PWA-Hintergrundbenachrichtigungen sind hier nicht implementiert.
- GitHub Pages ist öffentlich; niemals persönliche Backup-Dateien ins Repository laden.
- Dies ist eine PWA-Testversion, keine signierte App-Store-App.


Icon-Update: Kapsel-Icon (türkis/weiß) für iPhone-Home-Bildschirm.

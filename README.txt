# Wochentraining – Satz-Tracker (iPhone/PWA)

## Schnellstart (ohne Programmieren)
1) Ordner entpacken.
2) Hosting (am einfachsten):
   - Öffne https://app.netlify.com/drop
   - Ziehe den ENTpackten Ordner (oder den Inhalt) in das Drop-Feld.
   - Du bekommst sofort eine URL (https://....netlify.app)
3) Auf dem iPhone:
   - Öffne die URL in Safari
   - Teilen → „Zum Home-Bildschirm“
   - Fertig: läuft wie eine App (inkl. Offline-Cache)

## Daten
- Speichert lokal im Browser (localStorage) pro Gerät.
- Wochen werden automatisch archiviert, wenn eine neue ISO-Kalenderwoche beginnt (Mo–So).

## Export/Import
- Export: erzeugt eine JSON-Datei (Backup / Gerätewechsel)
- Import: lädt eine Export-Datei wieder ein
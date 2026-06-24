# COMPASS

Persönliches Trainings-Cockpit (Lauf) — live aus der intervals.icu-API, **eine einzige selbst-enthaltene HTML-Datei**. Läuft als GitHub Page.

- **Live:** https://guncanrun.github.io/compass/
- **Datenquelle:** intervals.icu API (Athlete `i183972`). Der API-Key wird einmalig im Browser (`localStorage`) hinterlegt und liegt **nie** im Repo.
- **Single-File:** `index.html` enthält alles (Chart.js via CDN, Hintergrund-Wasserzeichen als inline base64). Kein Backend, kein externes Asset.

## Features
Kurs-Hero/Kompass · Cockpit (Saisonform/Fitness/VO₂max/Form/A:C/A-Race) · 4 Chart-Tabs (Konsistenz/Form&Fitness/Vertikal/Erholung) · Pace-Predictor · Wochen-Grid mit Soll/Ist-Merge · Workout-Modal mit Deep-Links (intervals / **Strava** / **Hevy-Routine**).

## Deploy
Neue Version = `index.html` ersetzen und pushen (GitHub Pages, Branch `main`, /root).

---
*Interne Architektur-/Logik-Notizen liegen lokal in `COMPASS_CONTEXT.md` — bewusst **nicht** im öffentlichen Repo (siehe `.gitignore`).*

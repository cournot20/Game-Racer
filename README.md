# NEON RIFT 🚀

Ein 3D-Tunnel-Racer für den Browser – eine einzige HTML-Datei, keine Installation nötig. Läuft auf Smartphone und PC.

**▶ Jetzt spielen:** `https://DEIN-BENUTZERNAME.github.io/neon-rift/` *(Link nach Aktivierung von GitHub Pages anpassen)*

## Features

- Echte 3D-Grafik mit Three.js (Neon-Tunnel, Sternenfeld, Fahrtgefühl)
- **Solo-Modus:** Endlos-Runner mit steigendem Tempo und Highscore
- **Duell-Modus:** Split-Screen für 2 Spieler an einem Handy – Handy zwischen euch legen, jeder steuert seine Hälfte. Gleiche Hindernisse für beide (fairer Zufalls-Seed), wer zuerst 3 Runden gewinnt, siegt
- Touch-Steuerung (wischen), am PC Maus oder Pfeiltasten / A+D
- Soundeffekte per WebAudio-Synthesizer, Vibration bei Crash
- Highscore wird lokal im Browser gespeichert

## Steuerung

| Gerät | Steuerung |
|---|---|
| Smartphone | Finger aufs Display, links/rechts wischen |
| PC (Solo) | Maus ziehen oder Pfeiltasten ← → |
| PC (Duell) | Spieler 1: Pfeiltasten · Spieler 2: A / D |

Weiche den pinken Blöcken aus, sammle die grünen Orbs (+25 Punkte).

## Selbst hosten

Einfach `index.html` herunterladen und im Browser öffnen – das ist alles.

## Technik

Vanilla JavaScript + [Three.js](https://threejs.org/) r128 (via CDN). Keine Build-Tools, keine Abhängigkeiten, ~700 Zeilen Code.

## Lizenz

MIT – siehe [LICENSE](LICENSE).

---

*Erstellt mit Claude (Anthropic).*

# 🌱 Sprout Run

Ein lebendiger Jump-'n'-Run-Endlosläufer im Browser – gebaut mit HTML5 Canvas und Vanilla JavaScript. Spring über Hindernisse, stampf Gegner platt, sammle Münzen und schalte komplett verschiedene Helden frei. Kein Framework, kein Backend, alles in einer Datei.

**▶️ Live-Demo:** _https://enriquee-lab.github.io/sprout-run/_

---

## Features

- **Lebendige Spielwelt** im hellen Jump-'n'-Run-Stil: blauer Himmel, Wolken, grüne Hügel, Büsche, Gras-/Ziegelboden und schwebende Frageblöcke
- **Sechs echte Charaktere** (nicht nur Farbvarianten) – z. B. Sprout, ein Fuchs, ein Roboter, ein Slime und ein leuchtender Ninja – mit Live-Vorschau im Shop
- **Gegner mit Stomp-Mechanik:** watschelnde Monster laufen langsam heran; drauf springen besiegt sie und gibt Münzen
- **Steigende Schwierigkeit:** Das Spiel wird umso schneller, je länger du überlebst
- **Münzen sammeln** und im Helden-Shop für neue Charaktere ausgeben
- **Vollständiges Menü:** Hauptmenü mit Spielen/Charaktere; nach dem Tod zurück ins Menü oder direkt in den Shop
- **Pomodoro-Lernsperre:** Nach dem Verlieren startet ein 20-Minuten-Timer, in dem das Spielen gesperrt ist – so wird das Spiel zur Belohnung nach einer Lerneinheit (der Shop bleibt offen, die Sperre übersteht auch ein Neuladen)
- **Fortschritt bleibt gespeichert** (Highscore, Münzen, Charaktere) via `localStorage`
- **Spiel-Feel:** Doppelsprung, Ducken, Squash-Animation, Partikel und Screen-Shake

## Steuerung

| Taste | Aktion |
|-------|--------|
| `↑` / `Leertaste` | Springen |
| `↑` (nochmal in der Luft) | Doppelsprung |
| `↓` | Ducken |

Gegner besiegst du, indem du von oben auf sie springst.

## Lokal starten

Kein Build-Schritt nötig – einfach `index.html` im Browser öffnen.

## Tech-Stack

- **HTML5 Canvas** für Rendering und Animation
- **Vanilla JavaScript**: Game-Loop, Physik, Kollisionen, Stomp-Mechanik, Zustandsverwaltung
- **localStorage** für Fortschritt und freigeschaltete Charaktere

## Roadmap

- [ ] Soundeffekte und Musik
- [ ] Mehr Gegnertypen und ein Bonus-Level
- [ ] Touch-Steuerung für Mobilgeräte

---

Gebaut als Lernprojekt mit Claude.

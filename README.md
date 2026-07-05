# 🌱 Sprout Run

Ein lebendiger Jump-'n'-Run-Endlosläufer im Browser – gebaut mit HTML5 Canvas und Vanilla JavaScript. Spring über Hindernisse, stampf Gegner platt, sammle Münzen und schalte komplett verschiedene Helden frei. Kein Framework, kein Backend, alles in einer Datei.

**▶️ Live-Demo:** _https://enriquee-lab.github.io/sprout-run/_

---

## Features

- **Lebendige Spielwelt** im hellen Jump-'n'-Run-Stil: Himmel, Wolken, Hügel, Büsche, Gras-/Ziegelboden und schwebende Frageblöcke
- **15 verschiedene Charaktere** mit eigenen 2D-Zeichnungen (Fuchs, Ente, Dino, Roboter, Alien, Ritter, Slime, Ninja u. v. m.) – Live-Vorschau im Shop
- **15 kaufbare Maps** mit ganz eigenen Farbwelten (Wüste, Ozean, Vulkan, Nacht, Neon, Weltraum, Aurora …)
- **Power-ups im Lauf:** Jetpack (fliegen, solange man die Taste hält), Boost (kurz unverwundbar + Punkte) und **Energie-Orb** (anime-inspirierte Waffe, feuert automatisch leuchtende Orbs ab und zerstört Gegner)
- **Gleiten:** Sprungtaste gedrückt halten, um beim Fallen kurz zu schweben
- **Viele Gegner, score-gestaffelt:** watschelnde Monster (per Stomp besiegen), Bodenhindernisse (springen), Flieger (ducken), **schießende Gegner** (Kugeln ausweichen), **Sturzflug-Monster von oben** und ein neu gestalteter, bedrohlicher **Drache** – je weiter man kommt, desto mehr Gegnertypen tauchen auf
- **Extras-Shop:** kaufbares Startschild (5 Sek. unverwundbar beim Start) und Münz-Verdoppler
- **Progression:** wertvolle Skins & Maps kosten deutlich mehr – man muss dafür sammeln
- **Steigende Schwierigkeit:** Das Spiel wird schneller, je länger du überlebst
- **Pomodoro-Lernsystem:** 2 Versuche pro Runde, danach startet eine 20-Minuten-Lernzeit (eigener Lern-Screen mit ruhiger Landschaft); danach geht es weiter
- **Fortschritt bleibt gespeichert** (Highscore, Münzen, Charaktere, Maps, Extras) via `localStorage`
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

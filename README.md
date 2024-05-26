# Pac-Man Spiel



https://github.com/kruemmel-python/PacManPython/assets/169469747/13fc56c2-5bc0-4ad0-9fb0-8a4f8a82e309



Dieses Repository enthält den Code für eine einfache Implementierung des klassischen Pac-Man-Spiels in Python, unter Verwendung der `turtle`- und `freegames`-Bibliotheken.

## Spielbeschreibung

Das Spiel simuliert das klassische Pac-Man-Labyrinth, in dem der Spieler als Pac-Man Punkte sammelt und versucht, den Geistern zu entkommen. Das Ziel ist es, alle Punkte zu sammeln, ohne von den Geistern gefangen zu werden.

## Funktionsweise

- `pacman`: Eine `vector`-Instanz, die die aktuelle Position von Pac-Man im Labyrinth darstellt.
- `ghosts`: Eine Liste von Geistern, wobei jeder Geist durch seine Position (`vector`) und Bewegungsrichtung (`vector`) repräsentiert wird.
- `tiles`: Eine Liste, die das Labyrinth darstellt, wobei `1` eine Wand und `0` einen leeren Raum bedeutet.

## Steuerung

- Pfeiltaste nach rechts: Bewegt Pac-Man nach rechts.
- Pfeiltaste nach links: Bewegt Pac-Man nach links.
- Pfeiltaste nach oben: Bewegt Pac-Man nach oben.
- Pfeiltaste nach unten: Bewegt Pac-Man nach unten.

## Installation

Um das Spiel zu spielen, benötigst du Python und die `freegames`-Bibliothek. Installiere Python und führe dann den folgenden Befehl aus, um `freegames` zu installieren:

```bash
pip install freegames

# Pixel-Quest – das Spiel

Klassisches Jump & Run in 3 Welten (Gras, SciFi, Dungeon) mit Endboss, gebaut mit MakeCode Arcade.
Die Spiellogik steckt in der Erweiterung [pxt-pixelquest](https://github.com/theodorthg/pxt-pixelquest).
Grafiken und Welten liegen **im Projekt** und lassen sich direkt in MakeCode bearbeiten:

- **Assets-Tab:** alle Bilder, Animationen und Kacheln (Held, Gegner, Boss, Items, Hintergründe).
  Änderungen übernimmt das Spiel automatisch – die Namen müssen bleiben, wie sie sind.
- **Welten:** die Tilemaps `welt1` bis `welt3`, erreichbar über die Blöcke „Welt … Karte …“.
  Spielobjekte setzt man mit den Kacheln `pqStart`, `pqCoin`, `pqWalker`, `pqBoss` … (siehe README der Erweiterung).
- Weitere Welten (bis 9) einfach mit einem zusätzlichen „Welt 4 Karte …“-Block anlegen.

## In MakeCode öffnen

1. https://arcade.makecode.com öffnen
2. **Importieren** → **URL importieren** → `https://github.com/theodorthg/pixel-quest`
3. Es öffnet sich die Block-Ansicht; die Kategorie **Pixel-Quest** enthält alle Spiel-Blöcke.

## Steuerung

Pfeiltasten laufen, A springt (in der Luft nochmal = Doppelsprung), B greift an (Welt 3).

## Lizenz

MIT

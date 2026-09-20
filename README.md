# unouno

Ein kleines UNO-Kartenstapel-Spiel als einzelne HTML-Datei.

## Spielen

Einfach `index.html` im Browser öffnen. Es wird kein Server benötigt.

- **Nächste Karte** (oder Klick auf den Stapel, Leertaste, Enter): deckt die nächste Karte auf
- **Neu mischen**: mischt alle 108 Karten neu und beginnt von vorne, mit einer kleinen Misch-Animation
- Wenn der Stapel leer ist, wird das angezeigt und der Button deaktiviert
- Beim Ziehen, Mischen und beim leeren Stapel gibt es kurze Sounds. Der Lautsprecher-Button oben rechts schaltet den Ton aus und wieder an, die Einstellung wird im Browser gemerkt.

## Der Stapel

Der Stapel enthält alle 108 Karten eines UNO-Spiels:

- pro Farbe (Rot, Grün, Blau, Gelb): eine 0, die Zahlen 1 bis 9 je zweimal, sowie Aussetzen, Richtungswechsel und Zwei ziehen je zweimal
- viermal Farbwahl und viermal Vier ziehen

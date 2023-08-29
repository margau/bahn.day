# [bahn.day](https://bahn.day)

## HowTo contribute

### Ein Reisziel hinzufügen

- kopiere/forke das Repository, falls du das noch nicht getan hast
- eröffne einen neuen Branch für das Ziel
- kopiere den Ordner `archetypes/destination` und benenne ihn nach dem Ziel in `content/destination/<name>`
  - alternativ: `hugo new destination/<name>`, wenn du hugo installiert hast
- fülle die Datei `index.md` mit den Informationen zum Ziel aus
- lade mindestens ein Bild in den Ordner `img/` ein
- gebe die Metainfos am Beginn der Datei an, insbesondere:
  - fülle `title` und `description` aus
  - gebe deinem Bild eine Lizenz mit den `attribution`-Feldern an
  - referenziere ein Headerbild mit `imageResource: "img/<name>.jpg"`
  - falls dein Headerbild nicht von dir ist, nutze `imageAttribution` und `imageAttributionPlain` um den Autor und die Lizenz anzugeben.
Wenn das Bild von dir ist, entferne diese Felder einfach.
  - entferne alle tags, reachabilites und locations, die nicht zutreffen
  - füge nach Bedarf neue Tags hinzu
- wenn du magst, kannst du deine Änderungen lokal mit einem `hugo serve` testen
- eröffne einen PR mit deinen Änderungen
- warte auf review und merge. Danach sollte deine Reiseempfehlung innerhalb weniger Minuten online sein

### Sonstige Verbesserungen

- Hilf gerne mit, mach aber bei größeren Änderungen vorher ein issue zur Diskussion auf :)

### ToDos

- Dokumentation für die Erstellung von Reiseempfehlungen
- bessere Bild-Anzeige (Galerie etc.)
- mehr strukturierte Daten
- OSM als Karte einbinden
- ...

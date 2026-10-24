# Klangkoffer

Soundboard für die Besuche bei der Demenz-Gruppe im Seniorenheim (Klasse 10).
`index.html` im Browser öffnen (Handy, Tablet oder PC). Keine Installation nötig.

- **Alltag:** Türklingel, altes Telefon, Wecker, Kaffeemaschine, Wasserkocher, Standuhr, Kuckucksuhr, Kirchenglocke, Schreibmaschine, Autohupe
- **Natur & Geschichten:** Vogelgezwitscher, Frosch, Bach, Regen, Wind, Gewitter, Meeresrauschen, Kuh, Eule, Pferd (Hufe), knarrende Tür, Kaminfeuer, Dampflok
- **Rate-Modus:** Namen versteckt, Reihenfolge gemischt, „Auflösen“ pro Knopf
- **Dauerschleife:** Hintergrundklänge (Regen, Bach, Feuer …) laufen, bis man stoppt
- **Eigene Aufnahmen:** echte Audiodateien laden, als neuer Knopf oder als Ersatz für einen nachgebauten Klang (nur auf dem jeweiligen Gerät gespeichert)

## Woher kommen die Klänge?

Alle eingebauten Klänge sind **synthetisch nachgebaut** (Web Audio API: Töne und Rauschen, live erzeugt).
Es sind keine echten Aufnahmen und es gibt keine Lizenzfragen. Grob angenähert und eher schwer zu erkennen
sind vermutlich Kuh, Eule, Frosch, Kaffeemaschine und Dampflok. Bessere Klänge über „Eigene Aufnahmen“,
z.B. von Freesound.org (Filter „Creative Commons 0“) oder Pixabay Soundeffekte, oder selbst aufnehmen.

Die Lautstärke der Klänge wurde per Offline-Rendering gemessen und angeglichen (`lvl`-Werte im Code).

# Klangkoffer

Soundboard für die Besuche bei der Demenz-Gruppe im Seniorenheim (Klasse 10).
Die Schüler spielen die Klänge ab, die Gruppe rät. Beim Vorlesen spielt einer die Klänge, ein anderer liest.

`index.html` braucht den Ordner `sounds/` daneben. Wegen `fetch()` muss die Seite über einen Webserver laufen
(z.B. GitHub Pages oder `python3 -m http.server`), nicht per Doppelklick als Datei.

- **Alltag (20):** Wecker, Uhr tickt, Kirchenglocken, Autohupe, Klopfen, Staubsauger, Wasser eingießen, Sirene, Waschmaschine, Zähneputzen, Klospülung, Dose öffnen, Klatschen, Lachen, Schnarchen, Niesen, Baby weint, Trinken, Säge, Flugzeug
- **Natur & Geschichten (20):** Vögel, Frösche, Regen, Wind, Gewitter, Meer, Kuh, knarrende Tür, Kaminfeuer, Zug, Hund, Katze, Schaf, Hahn, Insekten, Schritte, Schwein, Huhn, Krähe, Wassertropfen
- **Ratespiel:** Name und Tipp sieht nur, wer das Handy hält. Zufällige Reihenfolge.
- **Geschichte:** Klänge in Buch-Reihenfolge mit Stichwort, einer tippt beim Vorlesen den nächsten an.
- **Aufnahmen:** pro Klang zwischen 2 Aufnahmen wählen oder eigene Datei laden (nur auf dem Gerät gespeichert).

## Quellen und Lizenz

Echte Aufnahmen aus dem Datensatz [ESC-50](https://github.com/karolpiczak/ESC-50) (Karol J. Piczak),
5-Sekunden-Ausschnitte von Freesound.org. Ausgewählt wurden **nur Clips mit CC0-Lizenz** (gemeinfrei).
Urheber und Original-Links pro Datei: `sounds/quellen.json` und in der App unter „Alle Urheber anzeigen“.
Bearbeitung: Stille am Anfang entfernt (bei kurzen Klängen), Lautheit angeglichen (-18 LUFS), Ein-/Ausblenden, MP3 96 kbit/s mono.

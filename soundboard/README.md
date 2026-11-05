# Klangkoffer

Soundboard für die Besuche bei der Demenz-Gruppe im Seniorenheim (Klasse 10).
Die Schüler spielen die Klänge ab, die Gruppe rät. Beim Vorlesen spielt einer die Klänge, ein anderer liest.

`index.html` braucht den Ordner `sounds/` daneben. Wegen `fetch()` muss die Seite über einen Webserver laufen
(z.B. GitHub Pages oder `python3 -m http.server`), nicht per Doppelklick als Datei.

- **Alltag (23):** Wecker, Uhr, Kirchenglocken, Autohupe, Klopfen, Staubsauger, Wasser eingießen, Wasser kocht, Waschmaschine, Zähneputzen, Klospülung, Dose öffnen, Schreibmaschine, Radio-Sender suchen, Jahrmarkt-Karussell, Windspiel, Klatschen, Lachen, Schnarchen, Niesen, Baby weint, Säge, Flugzeug
- **Natur & Geschichten (25):** Vögel, Bach, Regen, Gewitter, Sturm, Meer, Möwen, Kaminfeuer, Zug, knarrende Tür, Schritte auf Kies, Schritte im Schnee, Frösche, Kuh, Pferd, Schaf, Schwein, Hühner, Hahn, Hund, Katze, Specht, Eule, Krähe, Wolf
- **Ratespiel:** Name und Tipp sieht nur, wer das Handy hält. Zufällige Reihenfolge.
- **Geschichte:** Klänge in Buch-Reihenfolge mit Stichwort, einer tippt beim Vorlesen den nächsten an.
- **Aufnahmen:** pro Klang zwischen 2 Aufnahmen wählen oder eigene Datei laden (nur auf dem Gerät gespeichert).

## Quellen und Lizenz

Alles echte Aufnahmen aus drei freien Sammlungen. Urheber und Lizenz pro Datei: `sounds/quellen.json` und in der App unter „Alle Urheber anzeigen“.

- [ESC-50](https://github.com/karolpiczak/ESC-50) (Karol J. Piczak): 5-Sekunden-Ausschnitte von Freesound.org, Lizenz pro Clip CC0 oder CC BY (Namensnennung).
- [Blanket](https://github.com/rafaelmardojai/blanket): lange Naturklänge, Lizenz pro Klang CC0, CC BY oder gemeinfrei.
- [Moodist](https://github.com/remvze/moodist): CC0 oder Pixabay Content License; welche genau, gibt Moodist pro Datei nicht an. Die Pixabay-Lizenz erlaubt kostenlose Nutzung, verbietet aber, die Dateien einzeln weiterzuverbreiten oder zu verkaufen.

Bearbeitung: passende 25-Sekunden-Abschnitte ausgewählt, Lautheit angeglichen (-18 LUFS), Ein-/Ausblenden, MP3. Gewitter (Variante 1) = Donner (Moodist) + leiser Regen (Blanket) gemischt.

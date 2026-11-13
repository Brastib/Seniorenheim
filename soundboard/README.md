# Klangkoffer

Soundboard für die Besuche bei der Demenz-Gruppe im Seniorenheim (Klasse 10).
Die Schüler spielen die Klänge ab, die Gruppe rät. Beim Vorlesen spielt einer die Klänge, ein anderer liest.

`index.html` braucht den Ordner `sounds/` daneben. Wegen `fetch()` muss die Seite über einen Webserver laufen
(z.B. GitHub Pages oder `python3 -m http.server`), nicht per Doppelklick als Datei.

- **Zuhause (22):** Wecker, Uhr, Klopfen, knarrende Tür, Staubsauger, Wasser eingießen, Wasser kocht, Waschmaschine, Zähneputzen, Klospülung, Dose öffnen, Schreibmaschine, Radio-Sender suchen, Dia-Projektor, Zeitung blättern, Windspiel, Klatschen, Lachen, Schnarchen, Niesen, Baby weint, Säge
- **Tiere (16):** Vögel, Möwen, Specht, Eule, Krähe, Hahn, Hühner, Kuh, Pferd, Schaf, Schwein, Hund, Katze, Katze schnurrt, Frösche, Wolf
- **Natur & Wetter (10):** Regen, Gewitter, Sturm, Meer, Bach, Wasserfall, Kaminfeuer, Schritte auf Kies, Schritte im Schnee, Abend im Dorf
- **Unterwegs & Orte (12):** Kirchenglocken, In der Kirche, Im Café, Einkaufen, Straße in der Stadt, Autohupe, Scheibenwischer, Zug, Flugzeug, Jahrmarkt-Karussell, Ruderboot, Boot im Hafen
- **Suche** über alle Bereiche, **Sanft einblenden** (Hintergrund- und laute Klänge werden langsam lauter, Stopp blendet aus)
- **Ratespiel:** Name und Tipp sieht nur, wer das Handy hält. Zufällige Reihenfolge.
- **Geschichte:** Klänge in Buch-Reihenfolge mit Stichwort, einer tippt beim Vorlesen den nächsten an.
- **Aufnahmen:** pro Klang zwischen 2 Aufnahmen wählen oder eigene Datei laden (nur auf dem Gerät gespeichert).

## Quellen und Lizenz

Alles echte Aufnahmen aus drei freien Sammlungen. Urheber und Lizenz pro Datei: `sounds/quellen.json` und in der App unter „Alle Urheber anzeigen“.

- [ESC-50](https://github.com/karolpiczak/ESC-50) (Karol J. Piczak): 5-Sekunden-Ausschnitte von Freesound.org, Lizenz pro Clip CC0 oder CC BY (Namensnennung).
- [Blanket](https://github.com/rafaelmardojai/blanket): lange Naturklänge, Lizenz pro Klang CC0, CC BY oder gemeinfrei.
- [Moodist](https://github.com/remvze/moodist): CC0 oder Pixabay Content License; welche genau, gibt Moodist pro Datei nicht an. Die Pixabay-Lizenz erlaubt kostenlose Nutzung, verbietet aber, die Dateien einzeln weiterzuverbreiten oder zu verkaufen.

Bearbeitung: passende 25-Sekunden-Abschnitte ausgewählt, Lautheit angeglichen (-18 LUFS), Ein-/Ausblenden, MP3. Gewitter (Variante 1) = Donner (Moodist) + leiser Regen (Blanket) gemischt.

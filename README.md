Name des Projekts:	Empfehlungssysteme

Link zum MyBinder: 	[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HuseyinBgn/4RecomenderSystems/HEAD)

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem Empfehlungssysteme.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!

Zum Ausführen der einzelnen Code-Zeilen "STRG" + "Enter" Tasten drücken.
Beachten Sie keine der Zeilen zu überspringen, denn sonst kann es zu Fehlerhaften Ausführung führen.

1. Libraries installieren & importieren: 
- Librairies für die Datenverarbeitung und -visualisierung werden installiert und anschließend importiert.

2. Die Daten:
- "U.data.csv" Datei wird gelesen.
- Die ersten 5 Daten von U.data werden angezeigt.
- "Movie_Id_Titles.csv" Datei wird gelesen.
- Die ersten 5 Daten von Movie_Id_Titles werden angezeigt.
- Beide Tabellen werden zusammengefürht.

3. Explorative Datenanalyse:
- Tabelle Gruppieren nach "title" und Durchschnittswerte der Bewertungen/"rating" anzeigen.
- Tabelle nochmal Gruppieren nach "title" und Anzahl der Bewertungen/"rating" anzeigen.
- Oberen 2 Tabellen zusammenfuehren.
- Visualisierung der Anzahl der Bewertungen durch Histogramm.
- Visualisierung der Bewertungen.
- Joint Plot von Anzahl der Bewertungen und Bewertungen.

4. Ähnliche Filme empfehlen:
- Visualisieren der am häfigsten bewerteten Filme.
- Auswahl 2 spezieller Filme. "Star Wars" und "Liar Liar".
- Empfehlung der Filme die den oberen Filme am Nächsten stehen.
- Da zu wenige Bewertungen nicht Aussagekräftig sind, werden Filme mit mehr als 100 Bewertungen zur Empfehlung genommen.
- Es wird sichtbar, dass das Ergebnis mehr Sinn macht. 
- Da "Star Wars" und "Return of Jedi" Fortsetzungen voneinander sind. "The Mask" fällt auch unter der Kategorie Komödie.
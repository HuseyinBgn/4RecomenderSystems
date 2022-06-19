Name des Projekts:	Empfehlungssysteme
Link zum MyBinder: 	https://github.com/HuseyinBgn/4RecomenderSystems

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem Empfehlungssysteme.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!


1. Libraries installieren & importieren: 
- Hier werden die Librairies für die Datenverarbeitung und -visualisierung installiert und anschließend importiert.

2. Die Daten:
- "U.data.csv" Datei wird gelesen.
- Die ersten 5 Daten von U.data werden angezeigt.
- "Movie_Id_Titles.csv" Datei wird gelesen.
- Die ersten 5 Daten von Movie_Id_Titles werden angezeigt.
- Beide Tabellen werden zusammengefuerht.

3. Explorative Daten Analyse:
- Tabelle Gruppieren nach "title" und Durchschnittswerte der Bewertungen/"rating" anzeigen.
- Tabelle nochmal Gruppieren nach "title" und Anzahl der Bewertungen/"rating" anzeigen.
- Oberen 2 Tabellen zusammenfuehren.
- Visualisierung der Anzahl der Bewertungen durch Histogramm.
- Visualisierung der Bewertungen.
- Joint Plot von Anzahl der Bewertungen und Bewertungen.

4. Aehnliche Filme empfehlen:
- Visualisieren der am haefigsten bewerteten Filme.
- Auswahl 2 spezieller Filme.
- Empfehlung der Filme die den oberen Filme am Nächsten stehen.
- Da zu wenige Bewertungen nicht Aussagekraeftig sind, werden Filme genommen, die mehr als 100 Bewertungen haben.
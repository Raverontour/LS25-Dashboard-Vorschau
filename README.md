<div align="center">

# LS25 Dashboard

[![LS25 Dashboard – Hauptmotiv mit Spiel, Fahrzeugübersicht und Tablet](docs/images/dashboard_hauptmotiv.png)](docs/images/dashboard_hauptmotiv.png)

*Illustratives Projektmotiv. Aktuelle Ansichten der Anwendung findest du unten und in der Bildergalerie.*

**Live-Übersicht für Farming Simulator 25 – Desktop, Browser und Tablet**

![Status](https://img.shields.io/badge/Status-Vorschau_Testphase-e0a800)
![Plattform](https://img.shields.io/badge/Plattform-Windows-2672EC)
![Spiel](https://img.shields.io/badge/Farming_Simulator-25-78B928)

</div>

**Öffentliche Vorschau:** Hier findest du Bilder und Anleitungen. Dashboard und Begleitmod sind noch nicht zum Download freigegeben. Die gezeigten Funktionen befinden sich im Test.

**[Installation: Setup, Begleitmod und erster Start](docs/INSTALLATION.md)**

## Was ist das LS25-Dashboard?

Das **LS25-Dashboard ist deine zusätzliche Übersicht für den Landwirtschafts-Simulator 25**. Du kannst es neben dem Spiel auf einem zweiten Bildschirm oder im Browser auf einem Tablet nutzen. So behältst du deinen Hof im Blick, während du beispielsweise mit dem Traktor auf dem Feld arbeitest.

Die Anleitung beschreibt folgende Funktionen:

- **Fahrzeuge und Helfer:** Du siehst Fahrzeuge, angehängte Geräte, Geschwindigkeit, Füllstände und den Status von GIANTS-Helfern, AutoDrive und Courseplay. Farben helfen beim Erkennen: Grün bedeutet normaler Betrieb, Gelb beispielsweise Warten, Rot ein gemeldetes Problem.
- **Fuhrpark verwalten:** In der Fahrzeugliste findest du deine Maschinen. Im Vehicle Manager kannst du sie in eigene Gruppen und Untergruppen einteilen, etwa „Ernte“, „Transport“ oder „Hofarbeit“.
- **Aufträge überblicken:** Die Missionsanzeige zeigt verfügbare, aktive und erledigte Aufträge mit Feld, Fortschritt, Vergütung und weiteren Details. Aufgeklappt siehst du auch die vorgesehenen Mietfahrzeuge.
- **Produktionen überwachen:** Du erkennst, welche Rohstoffe vorhanden sind, welche Produkte entstehen und wo Nachschub nötig wird. Wenn passende Daten vorliegen, wird auch die verbleibende Laufzeit angezeigt.
- **Tiere versorgen:** Die Tierübersicht zeigt unter anderem Anzahl, Gesundheit, Produktivität sowie Futter- und Produktbestände.
- **Karte und Preise ansehen:** Auf der Karte findest du Fahrzeuge, Felder und Betriebe. Filter blenden einzelne Bereiche ein oder aus. Die Preisübersicht zeigt mit der passenden Erweiterung Bestände, Marktpreise und Preisbewegungen.
- **Leistung prüfen:** Der Systemmonitor zeigt verfügbare Werte zu Bildrate, Prozessor und Arbeitsspeicher.

### Wie funktioniert die Verbindung zum Spiel?

Ein Begleitmod namens `FS25_LS25DashboardMod` sammelt die Informationen im laufenden Spiel. Das Dashboard liest diese Daten und aktualisiert seine Anzeigen automatisch. Unterstützte Bedienaktionen werden wieder an das Spiel übergeben. Für aktuelle Werte müssen also der Begleitmod aktiviert und ein Spielstand geladen sein.

Zusätzliche Mods erweitern die Möglichkeiten. AutoDrive und Courseplay liefern beispielsweise ihre eigenen Helferinformationen. Für den Preis- und Bestandsreiter wird **FillTypeAmountPrice Display** benötigt. Die grundlegenden Fahrzeug-, Missions-, Produktions- und Tierdaten brauchen nicht alle diese Zusatzmods.

### So benutzt du es im Alltag

1. **Dashboard starten**, dann LS25 mit aktiviertem Begleitmod und deinem Spielstand öffnen.
2. **Links einen Bereich auswählen**, zum Beispiel Fahrzeuge, Missionen, Tiere oder Karte.
3. **Einträge anklicken**, um sie auszuwählen oder Details aufzuklappen. Bei Fahrzeugen steigst du am PC per Doppelklick ein; ein Rechtsklick zeigt das Fahrzeug auf der Karte.
4. **Die Karte mit dem Mausrad zoomen** und durch Ziehen verschieben.
5. **Ansicht anpassen:** Schrift, Farben, Fenstergröße und verschiedene Warnschwellen lassen sich einstellen. Die Register kannst du durch Ziehen umsortieren.

Ein praktisches Beispiel: Du erntest gerade ein Feld. Auf dem zweiten Bildschirm siehst du gleichzeitig den Füllstand deiner Fahrzeuge, den Status des Abfahrers, den Fortschritt deiner Aufträge und ob einer Produktion Rohstoffe fehlen.

## Projekt unterstützen

Wenn dir das Dashboard gefällt, kannst du die Weiterentwicklung freiwillig über PayPal unterstützen.

[![Projekt unterstützen über PayPal](docs/images/paypal_support.svg)](https://www.paypal.com/donate/?hosted_button_id=V25WZFAFG99QW)

Fragen, Feedback oder Austausch zum Dashboard? Hier geht es zur Discord-Community:

[![Zur Discord-Community](docs/images/discord_community.svg)](https://discord.gg/69eKtX9u2B)

## Einblicke und bebilderte Anleitung

### Fahrzeuge und Helfer

[![Fahrzeuge, Helfer und Missionspunkte](docs/images/vehicle_inspector.png)](docs/images/vehicle_inspector.png)

### Fahrzeugliste und Geräte

[![Fahrzeugliste mit Geräten und Füllständen](docs/images/vehicle_list.png)](docs/images/vehicle_list.png)

### Vehicle Manager

[![Fuhrpark in Gruppen und Untergruppen organisieren](docs/images/vehicle_manager.png)](docs/images/vehicle_manager.png)

### Missionen

[![Aufträge mit Details, Mietfahrzeugen und Missionskarte](docs/images/mission_display.png)](docs/images/mission_display.png)

### Produktionen

[![Produktion mit Rohstoffen, Rezepten und Beständen](docs/images/production_info_hud.png)](docs/images/production_info_hud.png)

### Tiere

[![Tierhaltung mit Versorgung und Bestandsübersicht](docs/images/animal_display.png)](docs/images/animal_display.png)

### Kartenübersicht

[![Kartenübersicht mit Fahrzeugen, Helfern und Hoffarben](docs/images/map_overview.png)](docs/images/map_overview.png)

### Systemmonitor

[![Systemmonitor mit Bildrate, Auslastung und Verbindungswerten](docs/images/system_monitor.png)](docs/images/system_monitor.png)

**[Dashboard Schritt für Schritt: acht Ansichten mit Pfeilen und Erklärungen](docs/TUTORIAL.md)**

Fahrzeuge auswählen, Füllstände lesen, Gruppen bilden, Aufträge verstehen, Produktionen versorgen und Karten bedienen.

[Alle aktuellen Screenshots](docs/SCREENSHOTS.md) · [Ausführliche Bedienung](docs/BEDIENUNG.md)

Bildstand: 27. September 2026 aus dem lokalen Teststand. Diese Vorschau enthält keine Programmdateien; ein Software-Download ist noch nicht freigegeben.

## Eigene Shop-Icons

[![Eigenes Fahrzeugfoto im Escape-Menü](docs/images/photo_escape_fahrzeuge.png)](docs/EIGENE_SHOP_ICONS.md)

**[Fotoanleitung mit sieben Bildern und Pfeilen](docs/EIGENE_SHOP_ICONS.md)**: Kamera in der Fahrzeugzeile öffnen, mit Maus und Mausrad ausrichten, **Weiter** zur Kontrolle und **Final auslösen** zum Speichern. Du bleibst im ursprünglichen Fahrzeug; Abbrechen per Maus oder Escape ist im gezeigten Mehrspielertest bestätigt.

Die eigenen Vorschau-Icons erscheinen auch im Escape-Menü in Fahrzeugübersicht und Karten-Auswahl. Mit installiertem Vehicle Inspector zeigt dessen Vorschau beim Darüberfahren mit der Maus das neue Bild. Die Bilder dokumentieren den Teststand, keine allgemeine Freigabe aller Modkombinationen.

## Verfügbarkeit

Ein geprüfter Download wird später angekündigt. Diese Seite enthält ausschließlich Dokumentation und Bilder; der Programmcode bleibt privat. Fragen und Rückmeldungen sind über den oben verlinkten Discord willkommen.

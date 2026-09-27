# LS25 Dashboard – Bedienungsanleitung

Bedienhinweise ergänzt am 27.09.2026. [Tutorial mit Pfeilen](TUTORIAL.md). Diese Seite enthält ausschließlich die Dokumentation des Teststands.

## Original-Mods vor der Nutzung

[VehicleInspector](https://www.farming-simulator.com/mod.php?mod_id=311140), [Vehicle Manager](https://www.farming-simulator.com/mod.php?mod_id=311112), [Production Info Hud](https://www.farming-simulator.com/mod.php?mod_id=313960), [Animals Display](https://www.farming-simulator.com/mod.php?mod_id=334131), [Missions Display](https://www.farming-simulator.com/mod.php?mod_id=309928) und [FillTypeAmountPrice Display](https://www.farming-simulator.com/mod.php?mod_id=309964) separat über GIANTS ModHub beziehen, sofern die jeweiligen Originalfunktionen gewünscht sind. FTAP ist für die Live-Preisliste erforderlich; native Tier-, Missions- und Produktionsbasisdaten sind nicht generell von diesen HUD-Mods abhängig. Die genaue Einordnung und weitere Originalquellen stehen unter [Voraussetzungen & Mods](MOD_VORAUSSETZUNGEN.md). Kein Reupload fremder Mods.

„Fill Type Amount Price“ hat im Dashboard eine Textsuche über bereits gelieferte Zeilen. Das bedeutet nicht, dass sämtliche Filter des Originalmods übernommen wurden.

## Schnellstart

Die wichtigsten Handgriffe für den Einstieg

### Portabler Start

Paket vollständig entpacken und START_DASHBOARD_NORTON_SAFE.bat öffnen. Voraussetzung ist 64-Bit-Python ab 3.10 mit Tkinter und passendem Pillow. Es gibt keine automatische Installation und keine Änderung von Windows-Sicherheitsrichtlinien. Nach dem Verschieben eine neue Verknüpfung erstellen.

### Ansicht wählen

Links im Dashboard wechselst du zwischen den Bereichen. Die Inhalte aktualisieren sich automatisch aus dem laufenden Spiel.

### Fahrzeuge bedienen

Ein einfacher Klick wählt ein Fahrzeug. Ein Doppelklick steigt ein. Mit Rechtsklick zeigst du es auf der Karte.

### Register anordnen

Halte ein linkes Registersymbol mit der Maus fest, ziehe es nach oben oder unten und lasse es an der gewünschten Stelle los. Die Reihenfolge wird automatisch gespeichert; im Browser funktioniert das entsprechend von links nach rechts.

### Eigenes Fenster

Auf dem PC öffnet ein doppelter Rechtsklick auf ein linkes Registersymbol dessen kompletten Inhalt in einem kleineren Extrafenster. Das gilt auch für Map Overview; auf Handy und Tablet ist diese Funktion ausgeschaltet.

### Karte bedienen

Mit dem Mausrad zoomst du, durch Ziehen verschiebst du die Karte. Zurücksetzen stellt die Ausgangsansicht wieder her.

## Registerkarten

Was hinter jedem Symbol steckt und welche Informationen dort erscheinen

### 🚜  Vehicle Inspector

Zeigt nur aktuell wichtige Fahrzeuge: gesteuerte Fahrzeuge, aktive KI-Helfer, AutoDrive, Courseplay und geparkte Fahrzeuge. Enthalten sind Status, Tempo, Feld, Fahrzeug, Anbaugeräte, Füllstände, Fahrername, Restzeit, Detailkarten und Tacho. Bei Zielankunft blinkt die ganze Zeile acht Sekunden.

### ☷  Fahrzeugliste

Zeigt alle betretbaren Motorfahrzeuge sowie eine getrennte Geräteübersicht. Status, Geschwindigkeit, Marke, Modell, Füllstände, Gruppe und Fahrer beziehungsweise KI-Helfer lassen sich direkt vergleichen.

### ▦  Vehicle Manager

Ordnet Fahrzeuge dauerhaft in eigene Gruppen und Untergruppen ein. Fahrzeuge können per Auswahl oder Ziehen zugeordnet, Gruppen umbenannt und Strukturen für jeden Spielstand getrennt gespeichert werden.

### 📖  Mission Display

Listet verfügbare und aktive Aufträge mit Missionsart, Feld, Fortschritt, Belohnung, Mietkosten und weiteren Details. Beim Aufklappen erscheinen die von GIANTS vorgesehenen Mietfahrzeuge mit Shopbild und Name. Die Symbolart lässt sich zwischen „Happy Looser Stil“ und „Farbig schön“ umschalten.

### ⌖  Player Position

Zeigt Spielerpositionen und vom Spiel bereitgestellte Zielpunkte. Verfügbare Teleport- oder Positionsaktionen erscheinen nur, wenn der aktuelle Spielzustand sie sicher unterstützt.

### △  Fill Type Amount Price

Bündelt Fülltyp, vorhandene Menge und Marktpreis. Pfeile zeigen Preisbewegungen: grün aufwärts, rot abwärts und neutral bei unverändertem Wert.

### ⚙  Production Info

Gruppiert Produktionsstandorte und klappt deren Ein- und Ausgaben auf. Bestand, Kapazität, Leistung, Restzeit und die einstellbare Warnampel machen Versorgungsengpässe sichtbar.

### 🐄  Animals Display

Zeigt Tierhaltungen mit Art, Anzahl, Kapazität, Produktivität, Gesundheit, Nachwuchs und Alter. Unterzeilen enthalten Eingangs- und Ausgangsprodukte mit Symbol, Richtung, gut lesbarem Signalbalken und – sofern die Quelle eine Rate liefert – Zeit bis leer beziehungsweise voll.

### 🗺  Map Overview

Stellt Fahrzeuge, Kombinationen, Anhänger, Geräte, KI-Helfer, Stationen, Produktionen, Tiere, Aufträge und weitere Punkte auf der Karte dar. Filter, Namen, Fruchtfarben und AutoDrive-Netz sind getrennt schaltbar.

### ▥  Systemmonitor

Zeigt Bildrate, Bildzeit, Prozessor- und Speicherwerte von Spiel und Dashboard sowie Objektzahlen. Im Multiplayer ergänzt er Verbindung, Spielerzahl und – wenn verfügbar – Ping.

## Statusfarben & Ampel

Auf einen Blick erkennen, ob Hilfe nötig ist

### GRÜN · Läuft normal

Ein Helfer oder Fahrsystem ist aktiv und arbeitet ohne erkennbares Problem.

### GELB · Wartet

Das Fahrzeug wartet etwa auf den Abfahrer oder einen AutoDrive-Ruf. Abschlussereignisse haben eigene Zählerfarben; siehe die Statuslegende im neuen Tutorial.

### ROT · Problem

Das Fahrzeug ist blockiert, die Arbeit wurde wegen eines Problems abgebrochen oder das Fahrsystem meldet einen Fehler.

### NEUTRAL · Kein Helfer

Es ist kein Helfer oder automatisches Fahrsystem aktiv. Weitere kleine Statussymbole zeigen Spieler, AutoDrive, Courseplay und angehängte Geräte.

## Fahrzeuge

Fahrzeuge, Fahrer, Füllstände und Karte gemeinsam

### Status

Fahrzeugart und Fahrzustand werden getrennt dargestellt. Die Fahrzeugfarbe folgt der Ampel-Legende.

### Tacho

Der runde Tacho zeigt Geschwindigkeit, Drehzahlbereich, Gang beziehungsweise D/N/R, Temperatur, Betriebsstunden und Kilometerstand. Der rote Drehzahlbereich warnt vor hoher Motordrehzahl.

### Füllstände

Zuerst steht die eigene Nutzlast oder der transportierte Tankinhalt des Fahrzeugs, danach folgen angehängte Geräte. Diesel, Harnstoff und weitere Betriebsstoffe stehen dahinter; Luft bleibt sichtbar und kommt zuletzt. Transport- und Verbrauchstank werden auch bei gleichem Fülltyp getrennt erkannt. Mit den Pfeilen wechselst du weitere Einträge.

### Aufteilung

Die Trennkante zwischen Liste und Karte ist verschiebbar. Status, Tacho, Feld und Fahrzeugbild behalten dabei eine lesbare Mindestgröße.

## Fahrzeugliste & Vehicle Manager

Finden, vergleichen und in Gruppen ordnen

### Fahrzeugliste

Status steht ganz links, danach folgen Tacho, Feld, Fahrzeug, Füllstände sowie Fahrer und KI-Helfer. Geparkte Fahrzeuge bleiben im Vehicle-Inspektor sichtbar und stehen immer oben.

### Vehicle Manager

Gruppen und Untergruppen strukturieren den Fuhrpark. Eine komplette Fahrzeugzeile kann ausgewählt und einer Gruppe zugeordnet werden.

### Sonderfahrzeuge

Fahrzeugähnliche Geräte ohne eigene Motorfahrzeugfunktion werden unter Anhänger und Anbauteile einsortiert.

## Produktionen & Preise

Produktionsketten und Marktbewegungen lesen

### Production Info

Ein einfacher Klick auf einen Produktionsbetrieb zeigt direkt alle zugehörigen Rezepte mit Zutaten und Ergebnissen. Ein zweites Untermenü und zusätzliche Doppelklicks sind nicht nötig.

### Produktionsampel

Kritische Bestände stehen zuerst. Rot kennzeichnet einen kritischen Vorrat beziehungsweise eine kritische Restlaufzeit, Grün den normalen Zustand. Auch bei inaktiven Rezepten bleiben kritische Vorräte sichtbar. Die Symbole links zeigen zuerst rote Warnungen.

### Füllstandsbalken

Die Balken nutzen fast die gesamte Zeilenhöhe. Unter 10 Prozent ist die Füllfarbe rot, ab 10 Prozent grün. Menge, Kapazität und Prozentwert stehen auf einer dunklen Fläche direkt im Balken und bleiben in beiden Zuständen gut lesbar.

### Fill Type Amount Price

Preise und Mengen werden je Fülltyp angezeigt. Grünes Dreieck nach oben bedeutet steigender Preis, rotes Dreieck nach unten fallender Preis; neutral bedeutet unverändert.

## Animals Display

Tierhaltungen und Versorgung

### Tierhaltung

Jede Haltung zeigt Tierart, Anzahl, Kapazität, Produktivität, Gesundheit, Vermehrung, Bestand nach Sorte/Alter und Preise.

### Aufklappen

Ein Klick auf den Pfeil oder die Füllstandsangabe öffnet die Tierhaltung samt der bereits geöffneten Überschrift „Füllstände“ und allen Fülltypen. Eingänge und Ausgänge sind durch Richtungstext und Dreiecke an beiden Seiten des Balkens erkennbar; bei vorhandener Rate erscheint zusätzlich „leer/voll in“. Bei Fahrzeugen, Geräten und Anhängern wird bewusst keine solche Zeitprognose angezeigt.

### Weide

Fehlt für den Fülltyp Weide ein GIANTS-Symbol, verwendet das Dashboard das eigene grüne Weidesymbol mit Holzzaun.

### Tierfilter

Die Tierarten-Schalter richten sich nach den im Spielstand vorhandenen Tierarten; zusätzliche Mapper-Tierarten können dadurch ebenfalls erscheinen.

## Missionen & Teleport

Aufträge und Ziele schneller erreichen

### Reihenfolge und Farbe

Erfüllte Missionen stehen oben, aktive darunter, verfügbare zuletzt. Erfüllte Hauptzeilen sind grün, aktive blau; verfügbare bleiben neutral mit gelbem Statussymbol. Die Erfüllungsangabe der Quelle hat Vorrang vor einer pauschalen 100-Prozent-Annahme.

### Spalten

Auftrag und Originalsymbol, Status, Auftragsgut, Feld, Fläche, Menü, Zeit, Vergütung und Fortschritt. „Auftragsgut“ ist bewusst kompakt. Bei langen Angaben die Details aufklappen. Zeit kann eine Frist oder eine von der Quelle gelieferte Schätzung sein; fehlende Werte werden nicht erfunden.

### Beschreibung

Die Beschreibung kommt aus der laufenden GIANTS- beziehungsweise Mod-Mission. Das funktioniert ohne feste Liste bekannter Zusatzmods, sofern die Mission die Beschreibung bereitstellt. Fehlt sie, bleibt eine Ersatzbeschreibung nötig.

### Start und Ziel

Grüne Punkte markieren Starts, rote Ziele. Nummern ordnen mehrere Positionen zu. Die Start-/Zielangaben bleiben in den aufgeklappten Details sichtbar.

### Missionskarte

Mausrad: zoomen. Linke Maustaste halten und ziehen: verschieben. Doppelklick: Karte groß in der Fenstermitte öffnen; erneuter Doppelklick: schließen. Feldnamen helfen bei der Orientierung; nähere Zoomstufen ergänzen umliegende Stationen und Produktionen, soweit Kartendaten vorliegen.

### Neue und erfüllte Aufträge

Das Abzeichen am Register blinkt bei neu erkannten Aufträgen mindestens 30 Sekunden. Der grüne Zahlenkreis zeigt erledigte Verträge. Bereits bekannte Aufträge eines Spielstands sollen beim erneuten Laden nicht als neue Verträge blinken.

### Originalmenü

Die Menüschaltfläche fordert die entsprechende Aktion im Spiel an. Für Happy-Looser-HUD-Aktionen muss die zugehörige Originalanzeige installiert und vom Begleitmod erkannt sein.

### Player Position

Spielerpositionen und verfügbare Zielpunkte stammen aus dem Spiel. Teleportaktionen werden nur bei gemeldeter Unterstützung angeboten. Ein doppelter Rechtsklick in der Geräteliste kann den Spieler neben das Objekt versetzen.

## Karten & Map Overview

Kartensymbole filtern und Positionen finden

### Filter

Fahrzeuge, Kombinationen, Anhänger, Geräte, Helfer, Stationen, Produktionen, Tiere, Aufträge und Sonstiges lassen sich einzeln ein- und ausblenden.

### Fruchtfarben und Namen

Schaltet die Feldfarben beziehungsweise Beschriftungen um. AutoDrive blendet das Streckennetz ein oder aus.

### Interaktion

Klick wählt, Doppelklick führt die passende Aktion aus. Zoomen und Verschieben funktionieren in beiden Kartenansichten gleich.

## AllRound-Leiste

Wetter, Kalender, Zeit, Geld und Hinweise

### Wetter

Sonne beziehungsweise Wettersymbol sowie aktuelle Temperatur, Tageshöchst- und Tagestiefstwert kommen aus denselben Spieldaten wie das GIANTS-HUD.

### Kalender und Zeit

Zeigt Jahr, Tag, Monat, Uhrzeit und Spielgeschwindigkeit. Verfügbare Klickaktionen entsprechen den im Spiel unterstützten Funktionen.

### Geld und Gebrauchtmarkt

Der Kontostand folgt der GIANTS-Farblogik. Ein blinkender gelber Hinweis erscheint nur bei einem neuen Gebrauchtfahrzeug-Angebot.

## Einstellungen & System

Darstellung, Leistung und Diagnose

### Darstellung

Farben, Schrift, sichtbare Bereiche und Produktionswarnungen lassen sich im Einstellungsfenster anpassen.

### Aktualisierung

Kurze Intervalle liefern flüssige Live-Werte. Unveränderliche Katalogdaten werden getrennt und selten geladen, um Mikroruckler zu vermeiden.

### Systemmonitor

Zeigt Bildrate und Bildzeit, CPU- und Arbeitsspeichernutzung von LS25 und Dashboard sowie Fahrzeug-, Helfer- und Produktionszahlen. Im Multiplayer kommen Verbindung, Spielerzahl und verfügbarer Ping hinzu.

### Problembericht

Fasst Verbindung, Protokoll, Spielstand und aktuellen Status für die Fehlersuche zusammen. Externe Dedicated-Server-CPU und -RAM können ohne Serverzugriff nicht gemessen werden.

### Handy und Tablet

Die Bedienoberfläche bleibt nutzbar, aber Desktop-Funktionen wie Extrafenster sind dort bewusst deaktiviert.

## Alle Einstellungen

Jede verfügbare Option, ihre Wirkung und der passende Einsatz

### Spielsteuerung

„Spiel starten“ verwendet den unter Pfade gewählten Spielstart oder eine erkannte Installation. „Normal beenden“ lässt LS25 über Rückfragen entscheiden. „Hart beenden“ kann ungespeicherten Fortschritt verlieren und ist nur für festgefahrene Prozesse vorgesehen.

### Datenquelle

Wählt die vom Begleitmod erzeugte vehicles.json. Nach dem Wechsel lädt das Dashboard Telemetrie, Karte, Produktionen und Preise aus demselben Profil neu.

### Pfade

Der Dashboard-Ordner zeigt den tatsächlich laufenden Programmstand und ist nicht zum Verschieben gedacht. „LS25-Programm“ bestimmt das zu startende Spielprogramm. „Spielstandordner“ bestimmt die Suche nach savegame1 usw. und den Import vorhandener Vehicle-Manager-Profile. „Automatisch“ entfernt die jeweilige Vorgabe. Die Telemetriedatei wird separat unter Allgemein ausgewählt. Kein Spielstand wird verschoben oder verändert.

### Mod-Übersetzungsreferenz

„Neu einlesen“ durchsucht die aktivierten Mods erneut nach übersetzbaren Namen. Das hilft bei Missions-, Produktions- und Fülltypbezeichnungen.

### Fenstergröße

Kompakt, Standard und Groß ändern die Hauptfenstergröße. Freie Größen, Spaltenbreiten sowie die Trennlinien zwischen Liste, Karte und Details werden ebenfalls gespeichert.

### Register-Reihenfolge

Die linken Registersymbole lassen sich per Ziehen frei nach oben oder unten verschieben. Desktop speichert die Reihenfolge in den Dashboard-Einstellungen; Tablet und Browser merken sie sich für das jeweilige Gerät.

### Fahrzeug-Aktualisierung

Zwei Sekunden ist der leistungsfreundliche Standard. Größere Intervalle reduzieren die Arbeit weiter, lassen Geschwindigkeit, Helferstatus und Restzeiten aber später reagieren.

### Karten-Aktualisierung

Die große Karten- und AutoDrive-Geometrie wird nur angefordert, solange eine Kartenansicht geöffnet ist. Eine Minute ist für große Karten und umfangreiche Netze der ruhige Standard.

### Leistung und Diagnose

CPU-Aufteilung reserviert weiterhin zwei logische Prozessoren außerhalb der LS25-Zuweisung. Das Dashboard darf wahlweise 2, 4 (Standard) oder 8 logische Prozessoren nutzen; zusätzliche werden mit LS25 geteilt. Keine automatische Erweiterung nach Last. Mindestens vier logische Prozessoren erforderlich. Die Diagnose schreibt zusätzliche Dashboard-Meldungen in das LS25-Protokoll.

### Farben und Schrift

Hintergrund, Fahrzeuglisten, Detailbereich und Schriftfarbe sind getrennt wählbar und bleiben nach dem Neustart erhalten. „Automatisch“ stellt gut lesbare Kontrastfarben wieder her.

### Missionssymbole

Die Originalsymbole der jeweiligen GIANTS- oder Mod-Mission haben Vorrang. Nur bei fehlenden Originalen verwendet das Dashboard Ersatzsymbole. Ein Fragezeichen bedeutet, dass für diesen Typ kein passendes Bild ermittelt werden konnte.

### Production-Info-Warnampel

Die rote Restzeit-Schwelle und die Vorratsschwelle sind einstellbar. Kritische Bestände werden rot hervorgehoben und zuerst angezeigt; normale Bestände grün. Inaktive Rezepte verbergen keine kritischen Vorräte.

### AllRound Extension

Diese Seite erscheint vollständig nur, wenn AllRound im laufenden Spiel erkannt wurde. Angezeigt werden ausschließlich tatsächlich verfügbare Originaloptionen; Änderungen werden an das Spiel gesendet und bestätigt.

### Karte und Bildschirmfoto

„Karte zurücksetzen“ stellt Zoom und Position der Hauptkarte zurück. „Bildschirmfoto speichern“ nimmt das Dashboard-Fenster auf und fragt immer nach Ziel und Dateiname.

## Voraussetzungen & Mods

Basisdaten und optionale Originalfunktionen unterscheiden

### Erforderlich für Live-Daten

Farming Simulator 25 mit geladenem Spielstand und dem passenden FS25_LS25DashboardMod. Das Dashboard liest dessen vehicles.json und die zugehörigen Daten im Telemetrieordner. Ohne Begleitmod gibt es keine aktuellen Live-Daten.

### GIANTS-Basisdaten

Fahrzeuge, Missionen, Produktionsbetriebe und Tierhaltungen werden aus den Spielsystemen exportiert. Zusätzliche Missions- und Kartenmods können diese Daten erweitern. Nicht jede Zusatzinformation wird von jedem Mod bereitgestellt.

### AutoDrive und Courseplay

Optional. Eigene Statusangaben, Ziele, Streckennetze und zugehörige Aktionen benötigen den jeweiligen im Spiel geladenen Mod. Ohne ihn bleiben die übrigen Fahrzeugdaten verfügbar.

### Happy-Looser-Anzeigen

Die Bridge sucht für Original-HUD-Bedienungen ausdrücklich nach Missions Display, Player Teleport Display, Fill Type Amount Price Display, Animals Display und Production Info HUD. Die jeweilige Originalaktion braucht die entsprechende erkannte Anzeige. Eine Dashboard-Grundansicht allein beweist nicht, dass jede Original-HUD-Aktion verfügbar ist.

### AllRound Extension

Originaloptionen und Originalbedienungen erscheinen nur bei erkannter AllRound-Integration. Wetter, Uhrzeit und Geld sind davon getrennte Spieldaten.

### Kein zusätzliches HL-HUD-Register

Das separate Register „HL-HUD Live“ entfällt. Die interne Bridge für andere unterstützte Anzeigen bleibt erhalten.

### Browser und Tablet

Nur im vertrauenswürdigen lokalen Netzwerk verwenden. Zugangsschlüssel nicht veröffentlichen und keine Router-Portfreigabe einrichten. Desktop-Extrafenster und lokale Prozesssteuerung sind keine allgemeinen Tablet-Funktionen.

### Fehlende Werte

Ein Strich, fehlende Schaltfläche oder ein Ersatzsymbol kann eine nicht vorhandene Quelle bedeuten. Erst Verbindung, geladenen Spielstand, passende Mod-Version und den Problembericht prüfen; keine Werte aus dem Screenshot erraten.

## Projekt & Impressum

Verantwortung, Unterstützung und Zweck des Dashboards

### Projekteigentümer

Raver ist Eigentümer und Projektverantwortlicher des LS 25 Dashboards.

### Unterstützer

Happy Looser und Achimobil unterstützen das Projekt bei Grundlagen, Rückmeldungen und praktischen Tests.

### Zweck

Das Dashboard bündelt Fahrzeug-, Helfer-, Missions-, Produktions-, Karten- und Systeminformationen in einer übersichtlichen zweiten Anzeige, ohne das Ingame-HUD zu überladen.

### Lokale Arbeitsweise

Spiel- und Einstellungsdaten werden lokal verarbeitet. Tablet-Zugriff läuft über die lokale Verbindung; die personalisierten Testkennungen senden keine Daten ins Internet.

### Unterstützer-Links

Geprüft: GIANTS ModHub und Discord von Happy Looser sowie das GitHub-Profil von Achimobil mit seinen öffentlichen LS25-Projekten.

### Drittanbieter

Optionale Mods und Spielressourcen bleiben Eigentum ihrer jeweiligen Urheber. AutoDrive, Courseplay, Happy-Looser-Anzeigen, Production Info und AllRound werden nur verwendet, wenn sie vorhanden sind.

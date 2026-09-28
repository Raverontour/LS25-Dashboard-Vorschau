# Voraussetzungen und Original-Mods

Geprüft am 25.09.2026 für Dashboard-Quellstand **2.03.20260924.1** und dessen Begleitmod. Neuere lokale Raster-/Bedienungskandidaten sind nicht enthalten.

## Für Live-Daten erforderlich

Farming Simulator 25, ein geladener Spielstand und der passende eigene Begleitmod `FS25_LS25DashboardMod.zip`. Ohne dessen Telemetrie gibt es keine aktuellen Daten. Windows benötigt außerdem 64-Bit-Python ab 3.10, Tkinter und Pillow. Diese Vorschauseite enthält weder Programmcode noch ein Installationspaket.

Ein ähnlich benannter Dashboard-Reiter macht den gleichnamigen Fremdmod nicht automatisch für alle Basisdaten erforderlich. Die Zuordnung wurde mit Dashboard und lokal geprüftem Begleitmod abgeglichen.

## Separat von den Originalseiten beziehen

| Original-Mod und direkter Download-Einstieg | Rolle im Dashboard |
|---|---|
| [VehicleInspector – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=311140) | Optional für die Originalintegration. Grundlegende Fahrzeugdaten kommen vom eigenen Begleitmod. |
| [Vehicle Manager – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=311112) | Optional für den Import bestehender Mod-Profile; lokale Dashboard-Gruppen sind davon unabhängig. |
| [Production Info Hud – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=313960) | Optional für Original-HUD und ergänzende Originalfunktionen. Produktionsketten nutzen auch den GIANTS-Produktionsmanager. Autor: Achimobil. |
| [Animals Display – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=334131) | Optional für native Tier-Basisdaten; für vollständige Original-HUD-Anbindung und zusätzliche Füllstandsinformationen separat installieren. Eigene Tierhaltungen werden auch direkt aus GIANTS gelesen. |
| [Missions Display – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=309928) | Optional für Missions-Basisdaten aus GIANTS. Original-HUD-Bedienung und ergänzende Mod-Metadaten benötigen die erkannte Originalanzeige. |
| [FillTypeAmountPrice Display – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=309964) | Für Live-Daten des Reiters „Fill Type Amount Price“ erforderlich: Der Export liest dessen Fülltyp-/Bestands-/Preislisten. Keine generelle Dashboard-Pflicht. |
| [PlayerTeleport Display – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=327619) | Für die persönlichen Punkte dieser Originalanzeige erforderlich; unabhängig registrierte Kartenziele sind davon zu unterscheiden. |
| [CoursePlay – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=331515) | Optional für Courseplay-spezifische Helferdaten und Bedienung. |
| [Precision Farming – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=318936) | Optional für tatsächlich verfügbare PF-Informationen, keine Pflicht für normale Fahrzeuge oder Missionen. |
| [AllRound Extension – GIANTS ModHub](https://www.farming-simulator.com/mod.php?mod_id=310611) | Optional für erkannte Originaloptionen/-aktionen. Wetter-, Uhrzeit- und Geld-Basiswerte sind unabhängig. |

Die HappyLooser-Anzeigen stammen vom jeweiligen Originalautor; Production Info Hud von Achimobil, Precision Farming von GIANTS Software und CoursePlay vom Courseplay-Team. Maßgeblich bleiben die Anforderungen auf den Originalseiten.

Für die optionale AutoDrive-Integration wurde keine passende offizielle FS25-ModHub-Seite verifiziert. Deshalb kein erfundener ModHub-Link: [Originalprojekt und Veröffentlichungen von Stephan-S/FS25_AutoDrive](https://github.com/Stephan-S/FS25_AutoDrive). AutoDrive ist keine generelle Startvoraussetzung.

## Installation und Suche

Gewünschte Mods einzeln von den verlinkten Originalseiten beziehen, als unveränderte ZIPs in den aktiven FS25-Mod-Ordner legen und im gewünschten Spielstand aktivieren. Keine Ersatz-Downloads von Spiegelservern verwenden. Die erkannte HUD-Fähigkeit entscheidet, ob eine Originalaktion angeboten wird.

Der Dashboard-Reiter „Fill Type Amount Price“ besitzt ein Suchfeld. Es filtert bereits übertragene Zeilen nach Text; nicht jede Filteroption des Original-HUDs ist nachgebaut. Codegrundlage: gemeinsamer Suchfilter in `refresh_mod_hud_views`, Live-Quelle `prices.json`. Der Begleitmod nutzt für Missionen `g_missionManager`, für Produktionsketten den ProductionChainManager und für Tier-Basisdaten native Tierhaltungen; FTAP dagegen dessen Original-Mod-Listen.

## Keine Weiterverteilung fremder Inhalte

Die offizielle Seite von [Production Info Hud](https://www.farming-simulator.com/mod.php?mod_id=313960) untersagt erneutes Hochladen außerhalb des ModHub und verweist auf den Originaldownload. Daher hier keine Mod-ZIP, Originalgrafiken oder fremden Modquellen. Auch GIANTS-Grafikdateien, Kartendateien und fremde Binärprogramme werden nicht gebündelt. Bedienbilder sind Dokumentations-Screenshots, kein wiederverwendbares Grafikpaket.


## Vorschau: fehlende Mods erkennen

Im nächsten Public-Update bleiben zugehörige HUD-Icons und Registerkarten bei fehlenden Moddateien grau sichtbar. Hover nennt den Mod; Doppelklick öffnet seine Originalseite. [Bedienung, Installationsschritte und Originalquellen](FEHLENDE_MODS.md). Im bisherigen Download ist diese Änderung noch nicht enthalten.

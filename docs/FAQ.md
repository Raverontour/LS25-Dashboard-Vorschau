# Häufige Fragen (FAQ)

Stand: 27. September 2026. Hinweise zur öffentlichen Windows-Testversion. Bestätigte Befunde, mögliche Ursachen und noch offene Korrekturen werden ausdrücklich unterschieden.

## Warum funktioniert der Fotomodus in einem neuen Singleplayer-Spielstand zunächst nicht?

Im aktuellen Teststand kann der Fotomodus beim ersten Laden eines **neuen, noch nicht gespeicherten Spielstands** deaktiviert bleiben. Der Mod benötigt eine dauerhaft gespeicherte Spielstandkennung. Fehlt der Speicherordner beim Laden, wird der fehlgeschlagene Versuch in dieser Sitzung noch nicht wiederholt.

### Vorläufiger Ablauf

1. Den Spielstand im Spiel **speichern** und warten, bis das Speichern abgeschlossen ist.
2. Das Spiel **normal beenden**.
3. Das **Dashboard schließen**.
4. Spiel und Dashboard wieder starten und **denselben gespeicherten Spielstand laden**.
5. Den Fotomodus erneut über die Kamera in der Fahrzeugzeile öffnen.

Dieser Ablauf ist eine Übergangslösung für den beschriebenen Erststartfehler, keine Voraussetzung vor jeder Fotoaufnahme. Entscheidend ist das erneute Laden des inzwischen gespeicherten Spielstands; dass das Dashboard dafür ebenfalls neu gestartet werden muss, ist nicht nachgewiesen. Sein Neustart gehört hier zum vollständigen Neustartablauf.

Im beobachteten Fall wurde später ein Fahrzeugfoto erfolgreich gespeichert. Falls der Fotomodus trotzdem nicht verfügbar ist, bitte die aktuelle Spiel-Log prüfen lassen. Nicht während des Speicherns gewaltsam beenden.

**Für das nächste Update vorgemerkt:** Die Kennung erneut anlegen beziehungsweise laden, sobald der Speicherordner verfügbar ist. Der Fotomodus soll dann nach dem ersten Speichern ohne Spielneustart funktionieren. Diese Korrektur ist noch nicht im veröffentlichten Paket enthalten.

[Zur bebilderten Fotoanleitung](EIGENE_SHOP_ICONS.md) · [Zur Installation](INSTALLATION.md)

## Installation und Verbindung

### Welche ZIP muss ich entpacken?

**Das gesamte Downloadpaket entpacken, die darin enthaltene Mod-ZIP geschlossen lassen.** Das Setup im Ordner Installation installiert das Dashboard. Die unveränderte `FS25_LS25DashboardMod.zip` gehört in den LS25-Mods-Ordner. Python ist im Windows-Setup enthalten. [Vollständige Installation](INSTALLATION.md).

### Warum fehlen neue Schaltflächen nach einem Update?

**Bei unserem Test startete eine alte angepinnte Verknüpfung einen älteren Dashboard-Ordner.** Schließe alte Dashboard-Fenster und starte die Anwendung direkt aus dem neuen Installationsordner. Prüfe anschließend das Ziel deiner Desktop- oder Taskleistenverknüpfung. Fehlende Knöpfe können auch von der jeweiligen Ansicht oder fehlenden Modfunktionen abhängen; sie beweisen allein keinen Versionsfehler.

### Warum zeigt das Dashboard keine aktuellen Spieldaten?

Prüfe zuerst: Ist der passende Begleitmod im Spielstand aktiviert, ist der Spielstand vollständig geladen und liest das Dashboard dessen aktuelle Telemetriedatei? Wähle nötigenfalls `vehicles.json` in den Einstellungen erneut aus. In Mehrspieler müssen Server und Client dieselbe Modversion verwenden. Ein geöffnetes Dashboard allein liefert noch keine Live-Daten. Fehlende Werte nicht durch Löschen von Spielständen oder Mod-Einstellungen zu beheben versuchen.

### Muss ich nach dem Austausch der Mod-ZIP neu starten?

Ja. Eine ersetzte ZIP ändert den bereits geladenen Mod nicht. Zuerst speichern und das Spiel schließen, bei einem Server auch diesen stoppen. Dieselbe neue Modversion auf Server und Clients einsetzen, dann neu starten. Das Dashboard für ein Dashboard-Update ebenfalls schließen. Alte Sicherungen außerhalb des Mods-Ordners aufbewahren.

### Geht das auf Tablet, Linux oder Mac?

Das bereitgestellte Setup ist für Windows. Die Browseransicht läuft über das Dashboard auf dem Windows-PC; das Tablet muss den Rechner im vertrauenswürdigen lokalen Netzwerk erreichen können. Verwende die im Dashboard angezeigte Adresse und den Zugangsschlüssel. Der Windows-PC und das Dashboard müssen weiterlaufen. Keine Router-Portfreigabe einrichten. Eigenständige Linux-/macOS-Pakete sind noch nicht bestätigt; ein echter Tablet-Test steht ebenfalls noch aus.

## Fotos und Vorschau-Icons

### Welche Kamera macht das Fahrzeugfoto?

Die kleine Kamera in der **Fahrzeug- oder Gerätezeile** öffnet den Fotodialog im Spiel. Die Kamera oben in der Dashboard-Werkzeugleiste erstellt einen Screenshot des Dashboards. Große Vorschau- und Detailbilder sind reine Anzeigen. [Bebilderte Fotoanleitung](EIGENE_SHOP_ICONS.md).

### Warum ist nach „Weiter“ noch kein Foto gespeichert?

Das ist beabsichtigt: **Weiter** öffnet die letzte Kontrolle. Erst **Final auslösen** speichert das Foto. **Zurück** führt zur vorherigen Stufe; **Abbrechen** oder Escape beendet den Vorgang ohne diese neue Aufnahme. Achte auf die Erfolgsmeldung im Spiel.

### Muss ich zum Fotografieren aussteigen oder den Helfer stoppen?

Beim getesteten aktuellen Ablauf bleibst du im ursprünglich besetzten Fahrzeug, auch wenn du ein anderes Objekt fotografierst. Ein laufender Helfer wird nicht automatisch angehalten. Fotoaufnahme und Rückkehr wurden auch bei einem fahrenden AutoDrive-Fahrzeug bestätigt. Das ist keine Garantie für sämtliche Fahrzeug- und Modkombinationen.

### Der Fotodialog verschwindet, die Maus fehlt oder die Kamera bleibt hängen – was tun?

**In älteren Testständen gab es mehrere verschiedene Ursachen:** einen zu strengen Vergleich zwischen Server- und Clientdaten, erzwungenes Aussteigen und Probleme mit Mausfokus beziehungsweise Kamerarückgabe. Diese Stellen wurden korrigiert und die betreffenden Abläufe getestet.

Prüfe zuerst, ob wirklich der neue Dashboard-Stand und auf allen Seiten derselbe neue Begleitmod geladen sind. Brich einen noch offenen Fotodialog mit Escape ab. Bei der früheren hängenden Kamerasteuerung half im beobachteten Fall ein Fahrzeugwechsel und Zurückwechseln; Escape allein half nicht zuverlässig. Tritt es erneut auf, notiere Fahrzeug, Helfer, besetztes Fahrzeug, letzten gedrückten Knopf und Uhrzeit und sichere die Log. Nicht jede neue Störung hat automatisch dieselbe Ursache.

### Wo sehe ich das fertige Bild?

Das eigene Vorschau-Icon wurde im Dashboard sowie im Escape-Menü in der Fahrzeugübersicht und bei der Fahrzeugauswahl auf der Spielkarte gezeigt. Mit installiertem Vehicle Inspector erscheint es außerdem in dessen Fahrzeugvorschau beim Darüberfahren mit der Maus. Vehicle Inspector ist für diese zusätzliche Anzeige erforderlich, nicht für sämtliche Dashboard-Funktionen.

### Werden meine Fotodateien auf dem Server gespeichert und an alle Spieler verteilt?

Die Bilddateien werden derzeit **lokal in den Mod-Einstellungen des Clients** gespeichert. Im Mehrspieler werden kleine Zuordnungs- und Aufnahmedaten geteilt; andere Clients erzeugen ihre Bilder lokal. Das ist keine Übertragung derselben fertigen PNG an alle Spieler. Eine dauerhafte Spielstandkennung und die Unterscheidung zwischen Einzel- und Mehrspieler sollen die Zuordnungen trennen. Für serverübergreifende Nutzung oder mehrere Clients wurde noch kein vollständiger Kompatibilitätstest bestätigt.

### Warum fehlen bei einem fremden Fahrzeug die Fotofunktionen?

Fotoaktionen berücksichtigen Hofzuordnung und Berechtigungen. Prüfe zuerst, ob du das Fahrzeug beziehungsweise Gerät auf deinem Hof bedienen darfst und ob die Daten aktuell sind. Eine fehlende Berechtigung ist kein Kopierschutz des Downloadpakets. Keine fremden Hofrechte umgehen oder Fotozuordnungsdateien zwischen Spielständen auf Verdacht kopieren.

### In einer Meldung stehen kaputte Umlaute. Ist das Foto beschädigt?

Beim beobachteten Fall war die Textcodierung der Erfolgsmeldung fehlerhaft, während das Foto gespeichert wurde. Die betroffenen Texte wurden anschließend korrigiert. Bei erneutem Auftreten den genauen Text oder einen Screenshot und die Modversion angeben; aus einem Darstellungsfehler allein folgt kein beschädigtes Bild.

## Helfer, Aufträge und Leistung

### Warum steht beim wartenden Drescher „blockiert“?

**Bestätigter früherer Erfassungsfehler:** Courseplay meldet Entladewarten als „muss entladen werden“. Diese Meldung wurde bisher nicht ausreichend berücksichtigt. Die neue Korrektur gibt diesem Wartezustand Vorrang vor der allgemeinen Blockieranzeige; ausdrückliche AutoDrive-Fehler behalten ihren Vorrang. Die gezielten automatisierten Tests bestehen, der erneute Live-Test dieser Korrektur steht noch aus.

Vergleiche die Anzeige mit der Meldung von Courseplay beziehungsweise AutoDrive im Spiel. Ein fast voller Korntank allein beweist kein Entladewarten. In einem anderen beobachteten Fall meldete AutoDrive tatsächlich einen festgefahrenen Fahrer; diese Warnung darf nicht pauschal in „Warten“ umbenannt werden. Für eine Fehlermeldung Fahrzeug, Feld, Füllstand und beide Anzeigen festhalten.

### Warum sind Spritz- oder Steineaufträge auf Thüringen sofort fertig?

**Die Ursache ist noch nicht bewiesen und der Fehler noch nicht behoben.** Er wurde im Spiel selbst beobachtet, auch im Singleplayer, und ist daher nicht allein durch Server-Lag oder die Dashboard-Anzeige erklärt. Mehrere Spritzaufträge endeten sofort; ein anderer desselben Typs blieb aktiv.

Better Contracts verändert die Fortschrittsberechnung. Eine reduzierte Abschlussschwelle erklärt Werte oberhalb von 100 Prozent, aber nicht von sich aus den sofortigen Abschluss eines unbehandelten Feldes. Unterschiede bei Unkraut-Zielzuständen und gespeicherter Steinmenge sind bisher nur Hinweise.

Für einen Vergleich Feldnummer, Auftragstyp, Zeitpunkt der Annahme, Fortschritt vor/nach der Annahme und Feldzustand festhalten. Wenn möglich eine Spielstandkopie **vor** der Annahme und eine nach dem Speichern sichern. Die tatsächlichen Unkraut-/Steindaten werden noch nicht vollständig vom Dashboard erfasst. Modvergleiche nur auf einer separaten Spielstandkopie durchführen; keinen produktiven Spielstand auf Verdacht bearbeiten oder Mods daraus entfernen.

### Es ruckelt – ist der Server überlastet?

Ein Ruckler allein beweist das nicht. Im bisherigen Test standen lokale Bildrate und Ping zur Verfügung; **echte Server-CPU- und RAM-Auslastung wird nicht gemessen**. Ein niedriger Ping schließt kurze Aussetzer nicht aus. Auch lokale Lade-, Shader- oder Bildverarbeitung kann stocken; welche Ursache zutrifft, muss einzeln geprüft werden.

Notiere die Uhrzeit und die gerade ausgeführte Aktion, zum Beispiel Fahrzeugwechsel, Reiterwechsel oder Fotoaufnahme. Sichere dazu lokale Log und, falls verfügbar, Server-Log sowie FPS/Ping. Ohne zeitgleichen Vergleich keine Ursache allein einem Mod oder dem Server zuschreiben. Zusätzliche Messungen der serverseitigen Aktualisierungsabstände sind vorgemerkt, noch nicht eingebaut.

### Windows zeigt „Keine Rückmeldung“. Soll ich sofort beenden?

Nicht allein aufgrund dieser Anzeige. Bei unserem Test lief ein langer Ladevorgang später weiter und ging zur Shader-Kompilierung über. Weitergeschriebene Logs zeigen Aktivität, beweisen aber ebenfalls nicht, dass die Bedienung bereits funktioniert. Ladefortschritt und Log gemeinsam beobachten. Normal beenden, wenn ein Abbruch nötig ist; erzwungenes Beenden kann ungespeicherte Änderungen verlieren und darf keinen laufenden Speichervorgang unterbrechen.

### Beim Reiterwechsel erscheint kurz „Mod nicht verfügbar“. Fehlt wirklich ein Mod?

Im beobachteten Fall lud die Missionsanzeige anschließend korrekt. Die kurzzeitige Meldung war damit irreführend und kein Nachweis für einen fehlenden Mod. Warte kurz auf die Daten. Bleibt die Meldung bestehen, prüfe den geladenen Spielstand, die Verbindung und die für diese Funktion benötigte Erweiterung. Für diesen Ladehinweis ist noch keine Korrektur bestätigt.

## Hilfe anfordern

### Welche Angaben helfen bei einem Fehlerbericht?

- Dashboard- und Begleitmod-Version sowie Einzel- oder Mehrspieler.
- Karte, betroffenes Fahrzeug beziehungsweise Feld und beteiligte Mods, insbesondere AutoDrive, Courseplay und Vertragsmods.
- Kurze Schritte zum Nachstellen: Was wurde geklickt, was wurde erwartet, was ist passiert?
- Ungefähre Uhrzeit, Screenshot und passende aktuelle Logauszüge; bei Bedarf eine separate Spielstandkopie.

Logs vor öffentlichem Teilen auf Zugangsdaten, Serveradressen und persönliche Pfade prüfen. Zugangsschlüssel zur Browseransicht nicht veröffentlichen. Die Dateien zunächst sichern; keine angebliche Lösung durch ungezieltes Löschen wichtiger Daten ausprobieren.

### Wird diese FAQ weiter ergänzt?

Ja. Die Sammlung basiert auf den tatsächlich besprochenen und geprüften Fällen. Neue bestätigte Erkenntnisse und Korrekturen sollen bei weiteren Updates eingearbeitet werden. Vermutungen bleiben ausdrücklich gekennzeichnet; ein vorgemerkter Punkt ist noch keine ausgelieferte Funktion.


## Fehlende Mods erkennen – Update 2.0.3.38

Im Update mit Begleitmod 2.0.3.38 bleiben zugehörige HUD-Icons und Registerkarten bei fehlenden Moddateien grau sichtbar. Hover nennt den Mod; Doppelklick öffnet seine Originalseite. [Bedienung, Installationsschritte und Originalquellen](FEHLENDE_MODS.md). Im bisherigen Download ist diese Änderung noch nicht enthalten.


## Was ändert sich in der Browseransicht im Public-Update mit Begleitmod 2.0.3.38?

Animals Display und Production Info HUD haben eigene Datenseiten. HUDs steuert dagegen nur die Anzeigen im Spiel. Die erste Datenabfrage startet nach dem Verbinden automatisch; Desktop-Reiter müssen dafür nicht angeklickt werden.

Production Info HUD trennt echte Rohstoff- und Produktlager von den Produktionsrezepten. Ein Rezept hat einen Aktivitätsstatus, keinen eigenen Lagerbalken. Ein Strich steht für eine fehlende Kapazität. Nach dem Update die Browserseite neu laden.

Die Änderungen sind im neuen Update enthalten: [Update herunterladen – Setup + Mod 2.0.3.38 + Anleitung (ShareMods)](https://sharemods.com/fmr8z38ao75v/LS25_Dashboard_2.03_Mod_2.0.3.38_Windows_Public_ENTPACKEN.zip.html). Der bisherige Download bleibt unverändert. [Versionshinweise](RELEASE_NOTES.md).

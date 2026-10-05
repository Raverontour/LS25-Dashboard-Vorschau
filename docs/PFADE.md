# Profile und Pfadprüfung

Stand: Public-Testversion 2.03.20261005.1, Sichtprüfung freigegeben.

## Einrichten

Unter **Einstellungen → Pfade** das tatsächlich verwendete LS25-Profil wählen. Auch frei benannte Profile auf anderen Laufwerken werden unterstützt. Gemeint ist der Ordner mit `log.txt` und `modSettings`, nicht `mods` oder ein einzelner `savegame1`-Ordner.

Sieben Quellen sind getrennt einstellbar: Profil, Spielprogramm, Spiel-Log, Mods, ModSettings, Spielstandordner und Live-Datei `vehicles.json`. Der angezeigte Dashboard-Ordner bezeichnet nur das laufende Programm.

„Automatisch“ trägt den ermittelten Pfad sofort sichtbar in das betreffende Feld ein. Der Modus bleibt dabei automatisch. Fehlende Pfade werden als Vorschlag benannt; ein nicht ermittelbarer Pfad wird nicht als Fund behauptet. Eigene Texteingaben und „Auswählen …“ sind manuelle Vorgaben.

„Übernehmen & prüfen“ speichert und prüft die neuen Angaben ohne Neustart. „Gespeicherte Pfade erneut prüfen“ prüft nur den gespeicherten Stand, nicht offene Eingaben. Eine neue Prüfnummer macht jeden Durchlauf sichtbar. Änderungen verwerfen alte Bestätigungen.

## Ergebnis verstehen

- **Grün / OK:** Nur die genannte Eigenschaft ist geprüft, etwa Ordner vorhanden und auflistbar oder Datei lesbar. Das bestätigt weder sämtliche Ordnerinhalte noch einen erfolgreichen Spielstart.
- **Gelbbraun / WARNUNG:** Eine Quelle fehlt oder eine Prüfung ist unvollständig.
- **Rot / FEHLER:** Die Quelle ist ungültig oder nicht lesbar.
- **Grau / OPTIONAL:** Eine nicht erforderliche Quelle ist nicht ermittelt oder noch nicht vorhanden.

Jeder Punkt wird einzeln geprüft. Eine vorhandene Live-Datei macht nicht alle anderen Punkte grün. Bei `vehicles.json` werden zusätzlich JSON-Lesbarkeit als Datenobjekt und Dateialter geprüft: über 60 Sekunden unverändert oder eine auffällige Zukunftszeit ergeben eine Warnung. Über 32 MB wird die JSON-Prüfung ausgelassen und entsprechend benannt. Dies bestätigt keine Modverbindung oder aktuelle Spielsitzung; dafür bleiben die getrennten Dashboard-Prüfungen zuständig.

Der Fotoordner wird zusätzlich automatisch aus ModSettings als `FS25_LS25DashboardMod/vehicle_photos` abgeleitet. Er bleibt vom Mod verwaltet und ist nicht frei umleitbar. Sein Fehlen ist optional. Ein vorhandener Ordner wird auf sichere Profilzuordnung und Auflistbarkeit geprüft, nicht jede Bilddatei.

## Bedienung

Die Pfadseite verwendet 13-Punkt-Schrift. Mausrad und Scrollleisten bewegen Pfadfelder beziehungsweise Bericht. Die sichtbare Trennkante über dem weißen Bericht mit gedrückter linker Maustaste hoch- oder herunterziehen. Die Prüftasten bleiben unten erreichbar. Die gewählte Teilung wird derzeit **nicht über einen Neustart gespeichert**.

## Profilwechsel, fehlende Daten und Update

Manuelle Vorgaben bleiben nach Neustart und bei automatischer Suche erhalten. Nach einem Profilwechsel separate Vorgaben kontrollieren: Eine manuelle Live-Datei hat Vorrang vor dem Profil. Zum Zurücksetzen im betroffenen Feld „Automatisch“ und anschließend „Übernehmen & prüfen“ wählen.

`vehicles.json` darf beim Einrichten noch fehlen. Den passenden Spielstand mit aktiviertem Begleitmod laden. Die Warteansicht nennt den erwarteten Pfad und bietet Zugang zur Pfadprüfung. Diese Einstellungen verschieben keine Spielstände und ändern keine LS25-Startparameter.

Bei einem reinen Dashboard-Update das Dashboard schließen und das neue Setup im bisherigen Dashboard-Ordner installieren beziehungsweise das vollständige portable Paket verwenden. Persönliche Einstellungen nicht löschen; anschließend die vollständige Buildnummer oben und die Pfade prüfen. Für diese Pfadkorrektur bleibt der Begleitmod unverändert. Nur ein ausdrücklich enthaltenes Mod-Update erfordert den Austausch nach Beenden von Spiel und Server.

Der Zusatzmod-Hinweis im Setup ist eine Informationsliste mit Original-Links und genau einem OK-Knopf, ohne Abhakfelder oder automatische Modinstallation.

Im Mehrspieler liest jedes Dashboard die lokale Datei seines Spieler-Mods im jeweiligen Profil. Hof- und Freigabefilter gelten weiter. Dies ist ein Codebefund, kein neuer Mehrclient-Livetest.

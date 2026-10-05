# Installation – LS25 Dashboard für Windows

## Update 2.03.20261005.1

Bei getrennter Auslieferung: `Setup_LS25_Dashboard_2.03.20261005.1.exe` direkt starten; `FS25_LS25DashboardMod.zip` geschlossen lassen. Ein äußeres Gesamt-ZIP muss nur entpackt werden, wenn ein solches tatsächlich angeboten wird. Das neue Setup enthält die aktualisierte Hilfe.

Dashboard vor dem Update schließen. Einstellungen nicht löschen; nach dem Update vollständige Buildnummer und **Einstellungen → Pfade** kontrollieren. Frei benannte Profile und individuelle Quellen werden unterstützt. „Automatisch“ zeigt den gefundenen Pfad im Feld; „Übernehmen & prüfen“ speichert. [Neue Pfadhilfe mit Prüfstatus und Bedienung](PFADE.md).

Diese Dashboard-Pfadänderungen benötigen keinen neuen Begleitmod. Der passende bestehende Stand ist 2.0.3.40; nur bei einem ausdrücklich neuen Mod-Update Spiel/Server beenden und Client/Server gemeinsam aktualisieren. Der Setup-Modhinweis ist eine reine Informationsliste mit OK, ohne Abhakfelder oder automatische Modinstallation.

Windows 10/11, 64 Bit. Das Gesamtpaket enthält Dashboard-Setup, Begleitmod und Anleitung. Das Windows-Paket ist als öffentliche Testversion erhältlich.

**[Bisherige Windows-Testversion herunterladen (älterer Stand)](https://sharemods.com/hsk5c6xu3an5/LS25_Dashboard_2.03_Windows_Public.zip.html)**

## 1. Gesamtpaket entpacken

Die heruntergeladene LS25-Dashboard-ZIP vollständig entpacken. Darin findest du den Ordner Installation, die Mod-ZIP und diese Anleitung.

## 2. Dashboard installieren

Im Ordner Installation die Setup_LS25_Dashboard.exe öffnen. Einen Installationsordner auswählen und Installieren anklicken. Anschließend kannst du ein Desktop-Symbol anlegen lassen. Python und die benötigte Laufzeit sind enthalten; eine separate Python-Installation ist nicht nötig. Für die Installation in einen eigenen Benutzerordner sind normalerweise keine Administratorrechte nötig.

## 3. Begleitmod einrichten

LS25 vorher beenden. FS25_LS25DashboardMod.zip unverändert und ungeöffnet in den Mods-Ordner von FarmingSimulator2025 kopieren. Dieser liegt normalerweise unter Dokumente > My Games > FarmingSimulator2025 > mods; bei umgeleiteten Dokumenten auch unter OneDrive. Eine ältere gleichnamige Moddatei vorher außerhalb des Mods-Ordners sichern und dann ersetzen. Nicht beide Versionen parallel behalten.

## 4. Spiel und Dashboard starten

LS25 starten, den Begleitmod für den gewünschten Spielstand aktivieren und den Spielstand laden. Das Dashboard über das Desktop-Symbol oder LS25Dashboard.exe im Installationsordner starten. Bei fehlenden Daten zuerst prüfen, ob der Mod aktiviert und der Spielstand geladen ist. Falls nötig unter Einstellungen die Telemetriedatei vehicles.json des Begleitmods auswählen.

## 5. Mehrspieler

Auf dem gestoppten Server dieselbe Mod-ZIP einsetzen und für den Spielstand aktivieren. Alle mitspielenden Clients benötigen dieselbe Modversion. Danach Server und Spiel starten. Das Dashboard läuft auf deinem Windows-PC; das Dashboard-Setup gehört nicht auf den Spielserver.

## 6. Browser und Tablet

Das Dashboard auf dem Windows-PC laufen lassen und dort den Browserzugang aktivieren. Die angezeigte Adresse auf dem Tablet im selben vertrauenswürdigen Netzwerk öffnen und den angezeigten Zugang verwenden. Keine Router-Portfreigabe nötig. Eine eigenständige Linux- oder macOS-Installation gehört nicht zu diesem Windows-Paket.

## Aktualisieren

Dashboard und Spiel schließen, auf einem Server auch den Server stoppen. Das neue Setup in denselben Dashboard-Ordner installieren und den Austausch bestätigen. Den Begleitmod auf Client und Server gemeinsam ersetzen. Eigene Einstellungen und Spielstände nicht löschen.

## Teststand und bekannte Grenzen

Dieses Paket ist ein Teststand. Der vorzeitige Abschluss einzelner Spritz- und Steineaufträge auf Thüringen ist noch nicht gelöst. Die neue Erkennung von Courseplays Entladewarten ist automatisiert geprüft, der erneute Servertest steht noch aus. Echte Server-CPU- und RAM-Messwerte sind nicht enthalten. Browseransichten wurden simuliert geprüft; ein echter Tablet-Test steht noch aus.

## Fotomodus beim ersten Spielstart

Bei einem neuen, noch nicht gespeicherten Singleplayer-Spielstand kann zunächst Speichern und ein Neustart nötig sein. [Vorläufigen Ablauf in den FAQ lesen](FAQ.md).


## Fehlende Mods erkennen – Update 2.0.3.38

Im Update mit Begleitmod 2.0.3.38 bleiben zugehörige HUD-Icons und Registerkarten bei fehlenden Moddateien grau sichtbar. Hover nennt den Mod; Doppelklick öffnet seine Originalseite. [Bedienung, Installationsschritte und Originalquellen](FEHLENDE_MODS.md). Im bisherigen Download ist diese Änderung noch nicht enthalten.


## 28. September 2026 – Public-Update mit Begleitmod 2.0.3.38

**Downloadstatus:** [Update herunterladen – Setup + Mod 2.0.3.38 + Anleitung (ShareMods)](https://sharemods.com/fmr8z38ao75v/LS25_Dashboard_2.03_Mod_2.0.3.38_Windows_Public_ENTPACKEN.zip.html). Der bisherige Download bleibt als ältere Version verfügbar.

- Fehlende und nicht aktivierte Zusatzmods bleiben als graue Icons und Register sichtbar. Hinweise unterscheiden Download und Aktivierung. Doppelklick öffnet bei fehlenden Mods die Originalquelle.
- Automatischer erster Datenabgleich nach jeder neuen Spielsitzung; geöffnete Browserseiten aktualisieren unabhängig vom Desktop-Reiter. Der erste Abgleich benötigt ungefähr eine halbe Minute.
- Animals Display und **Production Info HUD** als Browserseiten: Produktbilder, Füllstandsbalken und lesbare Zahlen. Bei Produktionen sind Rohstofflager, Produktlager und Rezepte getrennt; gemeinsam genutzte Lager werden nur einmal angezeigt.
- Spielanzeigen unter **HUDs** zusammengefasst; HL-HUD Live aus der Browsernavigation entfernt.
- Vorschaukärtchen in Karte und Map Overview: eigene Fotos bevorzugt, angehängte Geräte und verfügbare Aktionen Einsteigen, Job abbrechen oder Besuchen. Betretbare Fahrzeuge haben bei überlappenden Symbolen Vorrang.
- Anpassung an Fensterbreite und Tabletgröße; graue Register behalten beim Größenwechsel Farbe und Position. Optionale HUD-Daten blockieren den Start nicht mehr.
- Fotokennung wird beim Speichern erneut gesichert; bei neuen Spielständen kann ihre Anlage wiederholt werden, sobald der Speicherordner verfügbar ist.
- Setup mit Modliste und Originallinks, Update mit Datenerhalt und Windows-Deinstallation. Persönliche Daten bleiben standardmäßig erhalten; das Löschen erfordert eine zusätzliche ausdrückliche Auswahl.

**Installation:** Die äußere ZIP mit „ENTPACKEN“ im Namen vollständig entpacken. Setup ausführen, Begleitmod-ZIP geschlossen in den verwendeten Mods-Ordner legen und aktivieren. Bei einem Update denselben Installationsordner nutzen; keine vorherige Deinstallation nötig. Browserseite anschließend neu laden. Auf dem Server dieselbe Modversion einsetzen.

**Paketinhalt:** Setup-EXE, Begleitmod-ZIP und kurze HTML-Anleitung mit zehn Modlinks. Keine Sicherungen oder Testdateien.

Bekannte Grenzen: Der vorzeitige Abschluss von Spritz- und Steineaufträgen auf Thüringen bleibt offen. Echte Server-CPU-/RAM-Werte sind nicht enthalten. Der vollständige grafische Installationsdurchlauf wurde noch nicht geprüft; Simulation, Paket- und Startprüfung sind bestanden.


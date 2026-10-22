# Turniermanager

**Turnierverwaltung, die Poker versteht.**

Poker-Turnierverwaltung für Windows und Mac, aus professioneller Floor-Praxis entwickelt. Die öffentliche Beta verbindet Turnieruhr, Spielerzählung, Nachkäufe, Auszahlungen und eine separate Spieleranzeige.

[Website](https://turniermanager-beta.pages.dev/de/) · [Interaktive Demo](https://turniermanager-beta.pages.dev/de/#demo-open) · [English](README.en.md)

[Für Mac herunterladen — Apple Silicon und Intel](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-macos-universal.dmg) · [Für Windows herunterladen — x64](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe)

Kostenlose Beta **0.9.0-beta.2** vom 20. Oktober 2026. Privat und gewerblich kostenlos erproben, ohne Abo oder spätere Zahlungsverpflichtung für diese Erprobung. Künftige Versionen können andere Bedingungen haben. [Vollständige Beta-Bedingungen](BETA_TERMS.md).

Mac ist ad hoc signiert und nicht notarisiert; Windows ist unsigniert. Beim Öffnen können Sicherheitswarnungen erscheinen. Lies vor dem ersten Öffnen die [Installationshilfe](docs/INSTALLATION.de.md). Schutzfunktionen eingeschaltet lassen; eine Schadsoftware- oder Beschädigungswarnung nicht umgehen.

## Die Spieleranzeige

![Deutsche Lite-Spieleranzeige mit Uhr, Blinds, Spielerzahlen und Auszahlungen.](images/player-display-de.png)

## Der Arbeitsplatz

![Deutscher Lite-Arbeitsplatz mit Uhrbedienung, Spielerzahlen und Schnellaktionen.](images/workspace-de.png)

Echte Lite-Oberfläche, am 21. Oktober 2026 isoliert mit deutschen Beispieldaten gerendert; keine Aufnahme eines nativen App-Fensters. Die verwendeten UI-Komponenten sind gegenüber dem geprüften Beta-Code unverändert. Die PNGs wurden direkt aufgenommen und nicht nachbearbeitet. Die ursprünglichen englischen Fensteraufnahmen bleiben mit ihren [Bildnachweisen](checks/human-visual-acceptance.json) erhalten.

## Selbst ausprobieren

[Im Browser ausprobieren](https://turniermanager-beta.pages.dev/de/#demo-open)

Starte die Uhr, füge Spieler hinzu und buche Second Chances, ändere Blinds und Pausen und prüfe die Auszahlungen. Die Demo öffnet sich auf der Website und verwendet Beispieldaten. Deine Eingaben bleiben im Browser; Neuladen setzt die Demo zurück.

## Heute verfügbar

- Freezeout, Second Chance, Re-Entry und Rebuy mit passendem Add-on.
- Vorlagen, Blindstruktur, automatische Levelwechsel und geplante Pausen.
- Spielerzählung, passende Nachkäufe und Auszahlungsstaffeln.
- Separate Spieleranzeige mit eigenen Ansagen.
- Deutsch und Englisch, Hell-/Dunkelmodus am Arbeitsplatz sowie Dunkelgrün/Gold und Nachtblau für die Spieleranzeige.
- Lokales Speichern, Fortsetzen und zusätzliche Sicherungen.

Erster Probelauf: Vorlage bearbeiten und speichern, als Turnier laden, Spielerzahl eintragen, Auszahlungen und Spieleranzeige prüfen, Uhr starten. [Vollständige Hilfe](https://turniermanager-beta.pages.dev/de/help/) · [Fragen & Antworten](docs/FAQ.md).

## Pro-Ausblick

**Noch nicht enthalten.**

- Mehr Turnierformate
- Spieler und Sitzplätze
- Progressive Knockouts
- Eigener Auftritt
- Anpassbarer Arbeitsplatz

Ob und in welchem Umfang Pro entsteht, hängt von der Nutzung und dem Feedback zur Beta ab. Funktionen, Reihenfolge und Veröffentlichungstermine stehen noch nicht fest.

[Pro-Ausblick auf der Website](https://turniermanager-beta.pages.dev/de/#pro)

## Feedback

**Privat, ohne GitHub-Konto:** [Feedback per E-Mail](mailto:hybrid-larval-1l@icloud.com?subject=Turniermanager%20%E2%80%94%20Feedback). Das öffnet dein Mailprogramm; gesendet wird erst dort. Die [Feedbackseite](https://turniermanager-beta.pages.dev/de/feedback/) zeigt die Adresse zum Kopieren, falls kein Mailprogramm eingerichtet ist.

**Öffentlich, GitHub-Konto nötig:** [Fehler melden](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) · [Verbesserung vorschlagen](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=feedback.yml). Allgemeines Feedback benötigt nur eine Nachricht; Version und Betriebssystem sind freiwillig.

In der App: **Einstellungen → Programm**. Keine automatischen Logs oder Backups werden angehängt. Keine echten Teilnehmerdaten, vollständigen Backups oder Zugangsdaten veröffentlichen. [Sicherheitsprobleme privat melden](SECURITY.md). Eine Betreuung während eines Turniers oder eine feste Antwortzeit ist nicht zugesagt.

<details>
<summary>Technische Details und Prüfsummen</summary>

[macOS Universal · DMG](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-macos-universal.dmg) · 231.487.943 Byte

SHA-256: `f8f8c152b67eeda20e8e85fc7835026b84cd25bbf6180eccd3e0e220913469d9`

Geprüft auf einem Intel-iMac mit macOS 14.7 und einer ARM64-Mac-CI-VM mit Darwin 25.6.0. Das Paket ist ad-hoc signiert und nicht notarisiert. HDMI, jede Consumer-Konfiguration und die Installation auf einem MacBook sind damit nicht pauschal abgenommen.

[Windows x64 · Setup](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe) · 111.786.939 Byte

SHA-256: `e01c82ab14eb23217565d6262f1cc479de703cbac090be1f606303b3a3eac332`

Installation, normales Beenden und Wiederöffnen, Wiederaufnahme, Sicherung und Wiederherstellung wurden nativ in einer Windows-Server-2025-Datacenter-VM (10.0.26100, x64) geprüft. Installer und App sind unsigniert. Die Bildschirmaufnahmen sind auf 1024 Pixel Breite begrenzt; die Windows-Taskleiste verdeckt die unterste Ankündigungszeile. Ein physischer Windows-Rechner, HDMI und die native Tickerbewegung sind damit nicht vollständig geprüft. Details stehen in den [Windows-Bildnachweisen](checks/windows-human-visual-acceptance.json).

[Release & SHA-256](https://github.com/arnefranz-del/turniermanager-beta/releases/tag/v0.9.0-beta.2) · [Manifest](release-manifest.json) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [Third-party sources](docs/THIRD_PARTY_SOURCES.md)

</details>

## Produktunterlagen und Rechte

Dieses Repository enthält Produktunterlagen, Downloads und Feedback. Der App-Quellcode bleibt privat; es ist keine Open-Source-Freigabe der App. Rechte enthaltener Drittsoftware bleiben unberührt: [Hinweise](THIRD_PARTY_NOTICES.md) und [Quellen](docs/THIRD_PARTY_SOURCES.md).

Spielerprofile, Check-in, Seating, Tischbalancing, PKO/Bounty, Satellites, Remote-Steuerung und Synchronisation zwischen Rechnern sind nicht enthalten. Jeder Rechner hat seinen eigenen lokalen Stand.

Anbieter und Kontakt: Turniermanager · Arne Franz, Rita-Maiburg-Straße 40, 70794 Filderstadt. [E-Mail](mailto:hybrid-larval-1l@icloud.com).

Website-/Dokumentationsstand: 22. Oktober 2026. App, Installer und Release-Tag unverändert. Der Release-Tag bezeichnet den öffentlichen Dokumentations- und Manifeststand, keinen App-Source-Tag.

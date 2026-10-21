# Turniermanager Lite

[Website](https://turniermanager-beta.pages.dev/de/) · [English](README.en.md) · [Hilfe](https://turniermanager-beta.pages.dev/de/help/) · [Installation](docs/INSTALLATION.de.md) · [Fragen & Antworten](docs/FAQ.md)

**Pokerturniere vorbereiten und leiten. Für Windows und Mac.** Kostenlose Beta 0.9.0-beta.2, veröffentlicht am 20. Oktober 2026. Diese Beschreibung wurde am 21. Oktober überarbeitet; die App und die Downloads bleiben gleich.

## Nicht noch ein Pokerprogramm. Vom Floor. Für den Floor.

Bereite dein Turnier einmal vor und lade es beim nächsten Mal wieder. Während gespielt wird, behältst du Uhr, Spielerzahl und Preisgeld im Blick. Auf dem Fernseher oder zweiten Bildschirm sehen die Spieler Blinds, Pausen und Auszahlungen.

Turniermanager passt zum Homegame und zur Turnierleitung. Die App läuft lokal ohne Konto und ohne Internet. Sie zählt Spieler, verwaltet aber keine Teilnehmernamen oder Sitzplätze. Du kannst:

- Vorlagen für Freezeout, Second Chance, Re-Entry oder Rebuy mit passendem Add-on vorbereiten;
- Spieler hinzufügen, ein Ausscheiden erfassen und passende Nachkäufe eintragen;
- Uhr, Level und Pausen steuern und die Zeit bei Bedarf korrigieren;
- normale Auszahlungen anhand einer gespeicherten Regel automatisch aktualisieren lassen;
- die Spieleranzeige öffnen und eine Sicherung für später erstellen.

Ich bin Arne und seit über 15 Jahren im Live-Poker unterwegs. Ich kenne die Abläufe am Tisch und die Situationen, in denen es für die Turnierleitung schnell gehen muss. Diese Erfahrung steckt im Konzept und in der Bedienung von Turniermanager. Bei der Programmierung unterstützt mich KI.

## Die Beta ausprobieren

Du darfst diese Beta kostenlos privat oder als gewerblicher Veranstalter erproben. Dafür entstehen keine späteren Zahlungspflichten. Künftige Versionen können andere Bedingungen haben. Die vollständige Erlaubnis und ihre Grenzen stehen in den [Beta-Bedingungen](BETA_TERMS.md).

[Für Mac herunterladen](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-macos-universal.dmg) — Apple Silicon und Intel, DMG. Noch nicht mit einem Apple-Entwicklerzertifikat signiert und nicht notarisiert; macOS kann den Start blockieren.

[Für Windows herunterladen](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe) — x64, Setup. Noch nicht digital signiert; Windows kann eine Sicherheitswarnung anzeigen.

Lies vor dem ersten Öffnen die [Installationshilfe](docs/INSTALLATION.de.md). Mach vor dem ersten Turnier einen Probelauf mit deinem Rechner und Bildschirm. Lass die Schutzfunktionen eingeschaltet; eine echte Schadsoftware- oder Beschädigungswarnung nicht umgehen.

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

## Was klappt gut? Was nervt?

Ein paar Sätze reichen. **Privat und ohne GitHub-Konto:** [E-Mail an Arne](mailto:hybrid-larval-1l@icloud.com?subject=Turniermanager%20%E2%80%94%20Feedback). Der Link öffnet dein Mailprogramm; gesendet wird erst dort. Kein Mailprogramm eingerichtet? Kopiere die Adresse `hybrid-larval-1l@icloud.com` in deinen Webmail-Dienst. [Feedbackseite mit Kopierknopf](https://turniermanager-beta.pages.dev/de/feedback/).

**Öffentlich, GitHub-Konto nötig:** [Fehler melden](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) oder [Verbesserung vorschlagen](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=feedback.yml). Allgemeines Feedback braucht nur ein Textfeld; Version und Betriebssystem sind freiwillig.

In der App findest du die Links unter **Einstellungen → Programm**. „Feedback geben“ und „Fehler melden“ öffnen das öffentliche GitHub-Formular; die E-Mail-Alternative öffnet dein Mailprogramm. Die App überträgt keine Logs oder Backups automatisch. Erst auf GitHub beziehungsweise im Mailprogramm sendest du deine Nachricht ab. Keine echten Teilnehmerdaten, vollständigen Backups oder Zugangsdaten veröffentlichen. Sicherheitsprobleme bitte [privat melden](SECURITY.md). Eine Betreuung während eines Turniers oder eine feste Antwortzeit ist nicht zugesagt.

## Was hier öffentlich ist

Dieses Repository enthält Produktunterlagen, Downloads und Feedback. Der App-Quellcode bleibt privat; es ist keine Open-Source-Freigabe der App. Rechte enthaltener Drittsoftware bleiben unberührt: [Hinweise](THIRD_PARTY_NOTICES.md) und [Quellen](docs/THIRD_PARTY_SOURCES.md).

Spielerprofile, Check-in, Seating, Tischbalancing, PKO/Bounty, Satellites, Remote-Steuerung und Synchronisation zwischen Rechnern sind nicht enthalten. Jeder Rechner hat seinen eigenen lokalen Stand.

Anbieter und Kontakt: Turniermanager · Arne Franz, Rita-Maiburg-Straße 40, 70794 Filderstadt. [E-Mail](mailto:hybrid-larval-1l@icloud.com).

Der Release-Tag bezeichnet den öffentlichen Dokumentations- und Manifeststand, keinen App-Source-Tag. Die echte Herkunft der Beta-Bilder und die unterschiedlichen Build-Identitäten bleiben in den verlinkten technischen Nachweisen dokumentiert.

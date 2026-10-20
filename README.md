# Turniermanager Lite

[Website](https://turniermanager-beta.pages.dev/de/) · [English](README.en.md) · [Installation](docs/INSTALLATION.de.md) · [Fragen & Antworten](docs/FAQ.md) · [Beta-Nutzung](BETA_TERMS.md)

**Beta 0.9.0-beta.2 · 20. Oktober 2026.** Verfügbar für macOS Universal und Windows x64. Lies vor dem ersten Probelauf die Installations- und Signierungshinweise.

## Vom Floor. Für den Floor.

Nicht noch ein Pokerprogramm. Turniermanager bringt Uhr, Entries und Preisgeld an einen Arbeitsplatz. Bereite dein Turnier vor, buche Spieler und Nachkäufe als Anzahl und steuere die Uhr. Auf dem zweiten Bildschirm sehen die Spieler Zeit, Blinds und Auszahlungen.

Turniermanager Lite ist eine lokale Desktop-App für reguläre NLHE-Turniere mit anonymen Spielerzahlen. Du kannst:

- Vorlagen mit Blinds, Pausen und passenden Nachkäufen vorbereiten;
- Spielerzahlen und Nachkäufe als Mengen buchen und eine konkrete Buchung zurücknehmen;
- Uhr, Level und Pausen steuern und die Turnierzeit bei Bedarf korrigieren;
- Preisgeld und Gebühren getrennt verfolgen und Auszahlungsstaffeln prüfen;
- eine Spieleranzeige auf dem zweiten Bildschirm zeigen und lokale Sicherungen erstellen.

Arne Franz ist seit über 15 Jahren im Live-Poker aktiv und kennt die Arbeit als Floorman. Diese Erfahrung bestimmt das Konzept, die Turnierabläufe und die Produktarchitektur. Die Software wird mit Unterstützung von KI umgesetzt.

## Ausprobieren & Rückmeldung geben

Die veröffentlichte Beta darf privat und gewerblich kostenlos und freiwillig erprobt werden. Für diese Erprobung entstehen keine späteren Zahlungspflichten. Künftige Versionen können ein anderes Lizenzmodell haben. Die genauen Bedingungen stehen in [BETA_TERMS.md](BETA_TERMS.md).

[macOS Universal · DMG](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-macos-universal.dmg) · 231.487.943 Byte

SHA-256: `f8f8c152b67eeda20e8e85fc7835026b84cd25bbf6180eccd3e0e220913469d9`

Geprüft auf einem Intel-iMac mit macOS 14.7 und einer ARM64-Mac-CI-VM mit Darwin 25.6.0. Das Paket ist ad-hoc signiert und nicht notarisiert. HDMI, jede Consumer-Konfiguration und die Installation auf einem MacBook sind damit nicht pauschal abgenommen.

[Windows x64 · Setup](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe) · 111.786.939 Byte

SHA-256: `e01c82ab14eb23217565d6262f1cc479de703cbac090be1f606303b3a3eac332`

Installation, normales Beenden und Wiederöffnen, Wiederaufnahme, Sicherung und Wiederherstellung wurden nativ in einer Windows-Server-2025-Datacenter-VM (10.0.26100, x64) geprüft. Installer und App sind unsigniert. Die Bildschirmaufnahmen sind auf 1024 Pixel Breite begrenzt; die Windows-Taskleiste verdeckt die unterste Ankündigungszeile. Ein physischer Windows-Rechner, HDMI und die native Tickerbewegung sind damit nicht vollständig geprüft. Details stehen in den [Windows-Bildnachweisen](checks/windows-human-visual-acceptance.json).

[Release & SHA-256](https://github.com/arnefranz-del/turniermanager-beta/releases/tag/v0.9.0-beta.2) · [Manifest](release-manifest.json) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [Third-party sources](docs/THIRD_PARTY_SOURCES.md)

Was war beim Vorbereiten oder im Turnier unnötig schwer zu finden? [Gib Feedback](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=feedback.yml) oder [melde einen Fehler](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml). Ohne GitHub-Konto: [hybrid-larval-1l@icloud.com](mailto:hybrid-larval-1l@icloud.com). Keine echten Teilnehmerdaten, vollständigen Backups oder Zugangsdaten öffentlich hochladen. Sicherheitsprobleme bitte [privat melden](SECURITY.md).

## Was dieses Repository enthält

Hier liegen Produktbeschreibung, Hilfe, Versionshinweise und Feedback. Der App-Quellcode bleibt privat. Das öffentliche Produktrepo ist keine Open-Source-Freigabe der App. Hinweise und Rechte für tatsächlich enthaltene Drittsoftware gelten weiter und gehören zum jeweiligen Paket.

Spielerprofile, Check-in, Seating, Tischbalancing, Remote-Steuerung und Synchronisation zwischen Rechnern gehören nicht zu dieser Lite-Beta. Ein zweiter Rechner ist eine eigene lokale Instanz.

Anbieter und Kontakt: Turniermanager · Arne Franz, Rita-Maiburg-Straße 40, 70794 Filderstadt. E-Mail: [hybrid-larval-1l@icloud.com](mailto:hybrid-larval-1l@icloud.com).


Der öffentliche Release-Tag bezeichnet den Dokumentations- und Manifeststand dieses Repos. Er ist kein App-Source-Tag. Das Manifest unterscheidet die eingefrorene ausgelieferte Codebasis von den tatsächlichen privaten Build-Commits. Die Bilder sind echte Beta-2-Aufnahmen; ursprüngliche Paket-/Quellidentitäten und geprüfte Codegleichheit bleiben ausdrücklich dokumentiert.

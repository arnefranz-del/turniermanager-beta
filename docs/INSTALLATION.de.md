# Installation & erster Probelauf

[Zur Startseite](../README.md) · [English](INSTALLATION.en.md)

`0.9.0-beta.2` ist als kostenlose Mac-Beta freigegeben. **Windows ist noch nicht verfügbar.** Verwende das konkrete Paket und die SHA-256 aus dem [Release](https://github.com/arnefranz-del/turniermanager-beta/releases/tag/v0.9.0-beta.2). Geprüft: macOS 14.7 auf Intel-iMac und Darwin 25.6.0 in einer ARM64-CI-VM. Universal; ad-hoc signiert, nicht notarisiert. Diese Prüfung deckt nicht jedes Gerät und keine physische HDMI-Installation ab.

## macOS

1. Lade das DMG aus den [offiziellen Releases](https://github.com/arnefranz-del/turniermanager-beta/releases). Vergleiche Version, Dateiname und vollständige SHA-256-Prüfsumme mit dem Release.
2. Öffne das DMG und kopiere Turniermanager nach „Programme“. Wirf das DMG aus und starte die kopierte App.
3. Das vorgesehene Mac-Betapaket ist ad-hoc signiert und nicht notarisiert. Falls macOS den Start wegen des nicht verifizierten Entwicklers blockiert, prüfe Herkunft und Prüfsumme. Verwende nur den regulären Weg über „Systemeinstellungen → Datenschutz & Sicherheit → Dennoch öffnen“, sofern macOS ihn anbietet. [Apples Anleitung](https://support.apple.com/de-de/102445) erklärt den Ablauf.

Deaktiviere den Systemschutz nicht global. Eine Warnung über Schadsoftware oder eine beschädigte Datei darfst du nicht auf diesem Weg übergehen. Lade die Datei erneut aus dem offiziellen Release und melde den Befund. Für diese Beta wird kein Entfernen von Quarantäneattributen verlangt.

Ein Universal-Paket allein belegt keinen erfolgreichen Lauf auf jeder Intel- und Apple-Silicon-Konfiguration. Beachte die tatsächlich geprüften Geräte und Betriebssysteme im Release.

## Erster Probelauf

1. Öffne eine Vorlage und prüfe Name, Blindstruktur, Pausen und die passenden Nachkäufe. Speichere eine eigene Vorlage, wenn du Einstellungen wiederverwenden willst.
2. Lade die Vorlage als Turnier. Buche zunächst einige anonyme Spieler als Menge.
3. Starte die Uhr. Probiere Pause/Fortsetzen, eine Zeitkorrektur sowie Seat Open und die gezielte Rücknahme einer Buchung aus. Prüfe Spielerzahl, Chips und Preisgeld nach jedem Schritt.
4. Verbinde den zweiten Bildschirm, öffne die Spieleranzeige und wähle den passenden Bildschirm. Prüfe Lesbarkeit und Vollbild an diesem Gerät.
5. Erstelle eine `.tmbak`-Sicherung und bewahre sie außerhalb des App-Datenordners auf. Teste Wiederherstellen mit einer separaten Testinstanz, bevor du dich bei einem Turnier darauf verlässt.

Normales Beenden und endgültiges Abschließen sind verschiedene Aktionen. Ein aktiver gespeicherter Stand kann nach dem Neustart fortgesetzt werden. „Turnier endgültig beenden“ verlangt eine bewusste Bestätigung und beendet diese Durchführung; sie wird danach nicht als fortsetzbar angeboten. Vorlagen und externe Backups bleiben erhalten. Nach einer Unterbrechung kann die Uhr zur Prüfung angehalten sein. Vergleiche die Turnierzeit, korrigiere sie bei Bedarf und setze erst dann fort.

## Aktualisieren & entfernen

Erstelle vor einem Update eine Sicherung, beende die App normal und installiere die freigegebene neue Version. Prüfe danach Vorlage, gespeicherten Stand und Spieleranzeige. Die Beta hat keinen automatischen Rechner-Sync und keine automatische Updateinstallation.

Auf macOS entfernst du die App aus „Programme“. Lokale Benutzerdaten liegen getrennt vom Programm. Das Entfernen der App ersetzt weder eine Sicherung noch eine vollständige Datenlöschung.

Optionaler Prüfsummenvergleich im macOS-Terminal, mit deinem tatsächlichen Dateipfad:

```sh
shasum -a 256 /Pfad/zur/heruntergeladenen/Datei.dmg
```

Vergleiche alle 64 Zeichen mit dem Release. Eine Prüfsumme erkennt abweichende Bytes; die Herkunft des Downloads musst du ebenfalls prüfen.

Probleme: [Fehler melden](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) oder [E-Mail senden](mailto:hybrid-larval-1l@icloud.com). Bitte keine vollständigen Backups öffentlich anhängen.

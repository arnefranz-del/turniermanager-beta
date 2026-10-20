# Installation & erster Probelauf

[Zur Startseite](../README.md) · [English](INSTALLATION.en.md)

`0.9.0-beta.2` ist als kostenlose Beta für macOS Universal und Windows x64 freigegeben. Verwende das konkrete Paket und die SHA-256 aus dem [Release](https://github.com/arnefranz-del/turniermanager-beta/releases/tag/v0.9.0-beta.2). Geprüft: macOS 14.7 auf Intel-iMac, Darwin 25.6.0 in einer ARM64-CI-VM und Windows Server 2025 Datacenter (10.0.26100, x64) in einer CI-VM. Diese Prüfung deckt nicht jedes Gerät und keine physische HDMI-Installation ab.

## Windows x64

1. Lade `Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe` aus dem offiziellen Release. Vergleiche den vollständigen Dateinamen, die Größe und alle 64 Zeichen der SHA-256-Prüfsumme.
2. Beende eine bereits laufende Instanz normal und starte das Setup. Die Beta verwendet einen benutzerbezogenen Installer; eine systemweite Installation ist nicht vorgesehen.
3. Starte die installierte App über den normalen Programmeintrag. Prüfe vor dem ersten Turnier den gespeicherten Stand und die Spieleranzeige.

Installer und App sind unsigniert. Windows kann deshalb einen unbekannten Herausgeber oder eine SmartScreen-Warnung anzeigen. Prüfe Herkunft und Prüfsumme, bevor du entscheidest, ob du das Paket ausführen möchtest. Deaktiviere Windows-Schutzfunktionen nicht. Eine tatsächliche Schadsoftwarewarnung ist kein normaler Installationsschritt; brich ab und melde den Befund.

Der native Funktionstest lief auf Windows Server 2025 Datacenter in einer VM, nicht auf einem physischen Windows-10-/11-Rechner. Die Taskleiste verdeckt in den auf 1024 Pixel begrenzten Aufnahmen die unterste Ankündigungszeile; Bewegung und vollständige Darstellung des kurzen Tickers sind dadurch nicht nachgewiesen.

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

Auf Windows deinstallierst du über die reguläre App-Verwaltung. Der isolierte native Deinstallationstest hat den Erhalt der lokalen Benutzerdaten bestätigt. Sichere diese trotzdem vor einem Update oder einer Deinstallation; eine Deinstallation ist keine vollständige Datenlöschung.

Optionaler Prüfsummenvergleich in Windows PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "C:\Pfad\Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe"
```

Optionaler Prüfsummenvergleich im macOS-Terminal, mit deinem tatsächlichen Dateipfad:

```sh
shasum -a 256 /Pfad/zur/heruntergeladenen/Datei.dmg
```

Vergleiche alle 64 Zeichen mit dem Release. Eine Prüfsumme erkennt abweichende Bytes; die Herkunft des Downloads musst du ebenfalls prüfen.

Probleme: [Fehler melden](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) oder [E-Mail senden](mailto:hybrid-larval-1l@icloud.com). Bitte keine vollständigen Backups öffentlich anhängen.

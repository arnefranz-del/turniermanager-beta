# Installation & erstes Turnier

[Startseite](../README.md) · [English](INSTALLATION.en.md) · [Hilfe auf der Website](https://turniermanager-beta.pages.dev/de/help/)

Für die kostenlose Beta 0.9.0-beta.2 auf Windows x64 und Mac (Apple Silicon und Intel). Anleitung vom 21. Oktober 2026; die App ist unverändert.

<a name="install"></a>

## Installieren

### Mac

1. Lade die Mac-Datei über die [Downloads](https://turniermanager-beta.pages.dev/de/#downloads) herunter und öffne das DMG.
1. Kopiere Turniermanager nach „Programme“. Wirf das DMG aus und starte die kopierte App.
1. Die Beta ist ad hoc signiert, aber nicht mit einem Apple-Entwicklerzertifikat signiert und nicht notarisiert. Wenn macOS den unbekannten Entwickler meldet, prüfe zuerst die Herkunft der Datei. Lies [Apples Anleitung](https://support.apple.com/de-de/102445). Falls macOS es anbietet, kannst du nach einem Öffnungsversuch unter „Systemeinstellungen → Datenschutz & Sicherheit → Dennoch öffnen“ bewusst über den Start entscheiden.

### Windows x64

1. Lade die Windows-Datei über die [Downloads](https://turniermanager-beta.pages.dev/de/#downloads) herunter.
1. Öffne das Setup unter deinem Benutzerkonto und schließe die Installation ab.
1. Starte die installierte App über ihren Programmeintrag. Das Paket ist unsigniert; Windows kann deshalb einen unbekannten Herausgeber oder eine Sicherheitswarnung anzeigen.

Prüfe bei einer Warnung die Herkunft der Datei und entscheide bewusst, ob du sie öffnen möchtest. Lass Virenschutz und SmartScreen eingeschaltet. Eine Schadsoftware- oder Beschädigungswarnung nicht umgehen: Brich ab, lade die Datei erneut aus dem offiziellen Release und melde den Befund. [Microsoft erklärt die Windows-Schutzfunktionen](https://support.microsoft.com/de-de/windows/security/windows-security/app-browser-control-in-the-windows-security-app).

<details>
<summary>Optional: die heruntergeladene Datei prüfen</summary>

Unter „Technische Details und Prüfsumme“ beim Download stehen Dateiname, Größe, getestete Systeme und SHA-256. Technisch erfahrene Nutzer können die Prüfsumme vergleichen: auf dem Mac mit `shasum -a 256 DATEI.dmg`, in Windows PowerShell mit `Get-FileHash DATEI.exe -Algorithm SHA256`. Ersetze den Dateipfad und vergleiche alle 64 Zeichen. Eine passende Prüfsumme bestätigt gleiche Dateiinhalte; sie garantiert nicht, dass eine Datei sicher ist.

</details>

### Später aktualisieren oder entfernen

Erstelle vor einem Update eine Sicherung, beende die App normal und installiere die neue offizielle Version. Prüfe danach den gespeicherten Stand und die Spieleranzeige. Updates werden nicht automatisch installiert.

Auf dem Mac entfernst du die App aus „Programme“, auf Windows über die reguläre App-Verwaltung. Dabei können lokale Benutzerdaten erhalten bleiben. Eine Deinstallation ersetzt weder eine Sicherung noch eine vollständige Datenlöschung.

<a name="first"></a>

## Dein erstes Turnier

1. Wähle auf der Startseite eine Vorlage und öffne „Bearbeiten“ oder lege mit „Neue Vorlage erstellen“ eine eigene an.
1. Prüfe Format, Startstack, Buy-in, Blinds und Pausen. Sichere deine Einstellungen mit „Vorlage speichern“ für weitere Turniere.
1. Lade sie über „Turnier laden“. Mit „Spieler hinzufügen“ gibst du die Spielerzahl ein; du erfasst keine Teilnehmernamen.
1. Prüfe unter „Preisgeld & Deals“ die Auszahlungsregel und den passenden Bereich für die Zahl der Turniereinstiege. Speichere eigene Änderungen mit „Änderungen übernehmen“.
1. Öffne die Spieleranzeige für den angeschlossenen Bildschirm. Die nächsten Schritte stehen unter [Spieleranzeige](#display).
1. Drücke „Uhr starten“. Normale Level und geplante Pausen wechseln automatisch. „Pausieren“ hält die Uhr bewusst an, „Fortsetzen“ lässt sie weiterlaufen.
1. Mit „Seat Open −1“ erfasst du einen ausgeschiedenen Spieler. „Rückgängig“ nimmt eine ausgewählte geeignete Aktion zurück. Nutze für Nachkäufe den zum Turnier passenden Knopf.

Eine Vorlage enthält die Regeln für deinen nächsten Abend. Ein neues Turnier startet mit leeren Zählern und einer neuen Uhr. Ein schon laufender Abend wird über seinen gespeicherten Stand fortgesetzt. Probiere das vor dem ersten Einsatz mit Beispieldaten aus.

„Entries“ sind gezählte Turniereinstiege. Diese Zahl ist etwas anderes als die Zahl der noch aktiven Spieler. Ein Ausscheiden ändert nicht rückwirkend die bereits gezählten Entries.

<a name="display"></a>

## Spieleranzeige auf den zweiten Bildschirm legen

1. Schließe Fernseher oder Monitor an und wähle in den Anzeigeeinstellungen deines Rechners „Desktop erweitern“.
1. Öffne in der App „Spieleranzeige öffnen“.
1. Wähle unter „Spieleranzeige“ den Zielbildschirm und nutze die Vollbildfunktion. Du kannst das Anzeigefenster auch auf den zweiten Bildschirm verschieben.
1. Prüfe am tatsächlichen Gerät, ob Uhr, Blinds, Pausen und Auszahlungen gut lesbar sind.

Eine manuelle Ansage überlagert die Texte aus Phase, Pause oder Vorlage. Über „Manuelle Ansage entfernen“ kehrst du zu diesen Texten zurück. Eigene Ansagen werden beim Sprachwechsel nicht automatisch übersetzt.

Die App steuert weder den Fernseher noch die HDMI-Verbindung fern. Wenn der Bildschirm fehlt, prüfe zuerst Kabel und Anzeigeeinstellungen des Rechners.

<a name="payouts"></a>

## Auszahlungen verstehen

Wenn eine gültige Auszahlungsregel gespeichert ist und ein Bereich zur gezählten Zahl der Turniereinstiege passt, aktualisiert die App die normalen Auszahlungen automatisch. Du musst nicht jede neue Anzeige einzeln freigeben.

Änderst du die Regel unter „Preisgeld & Deals“, speichere die Änderung mit „Änderungen übernehmen“. Fehlt ein passender Bereich, ergänze ihn. „Seat Open −1“ verringert die aktive Spielerzahl, aber nicht die bereits gezählten Turniereinstiege.

Nachkäufe können das Preisgeld erhöhen. Ob eine bestimmte Art von Nachkauf auch bei der Auswahl des Auszahlungsbereichs mitzählt, stellst du in der Regel ein. Gebühren und Preisgeld werden getrennt behandelt.

Eine ICM-Berechnung oder ein angezeigter Dealvorschlag ist noch keine Vereinbarung. Ein Deal braucht eine eigene bewusste Bestätigung. Vereinbarte feste Beträge und bereits übernommene Deals folgen ihren eigenen Schutzregeln; sie sind von den normalen automatischen Auszahlungen zu unterscheiden.

<a name="backup"></a>

## Speichern, schließen und sichern

### Schließen und später weitermachen

Wenn du die App normal schließt, bleibt dein Turnier gespeichert. Beim nächsten Öffnen kannst du es fortsetzen. Prüfe dabei die Uhr: Nach einer Unterbrechung kann sie angehalten sein. Vergleiche Restzeit und Phase, korrigiere sie bei Bedarf und setze erst dann fort.

„Turnier beenden …“ ist eine andere Aktion: Nach deiner Bestätigung wird dieses Turnier nicht mehr als laufender Stand zum Fortsetzen angeboten. Das bedeutet nicht, dass alle Archive oder externen Sicherungen sicher gelöscht sind.

### Eine zusätzliche Sicherung erstellen

1. Öffne „Einstellungen → Sicherung“ oder den vorhandenen Sicherungszugang im Menü.
1. Wähle „Backup erstellen“.
1. Speichere die `.tmbak`-Datei außerhalb des App-Datenordners, zum Beispiel auf einem USB-Stick.

Automatisches Speichern hilft auf diesem Rechner. Eine zusätzliche Sicherungsdatei hilft, wenn der Rechner oder seine Daten ausfallen. Die Datei ist nicht verschlüsselt; bewahre sie entsprechend auf und veröffentliche sie nicht.

### Eine Sicherung wiederherstellen

1. Sichere zuerst den Stand, den du jetzt auf dem Rechner hast.
1. Öffne „Sicherung“ und wähle „Backup wiederherstellen“. Öffne die gewünschte `.tmbak`-Datei.
1. Prüfe Datum, Version und Inhalt. Nach deiner Bestätigung ersetzt die Wiederherstellung den lokalen Datenstand. Sie führt keine zwei Turnierbestände zusammen.
1. Prüfe danach Vorlagen, gespeicherte Turniere, Spielerzahlen, Uhr, Auszahlungen und Anzeigeeinstellungen.

Jeder Rechner hat seinen eigenen Stand. Eine Sicherungsdatei synchronisiert keine Geräte. Falls Wiederherstellung oder Speichern fehlschlagen, erhalte die vorhandenen Dateien und melde die genaue Fehlermeldung. Lösche keine Dateien auf Verdacht.

<a name="feedback"></a>

## Rückmeldung direkt aus der App

Öffne „Einstellungen → Programm“. „Feedback geben“ öffnet das öffentliche GitHub-Feedbackformular, „Fehler melden“ das Fehlerformular. Beide brauchen ein GitHub-Konto. Appversion und Plattform stehen bereits im sichtbaren Formular; du kannst sie prüfen.

Darunter steht die E-Mail-Adresse als Alternative ohne GitHub-Konto. Der Klick öffnet dein Mailprogramm. Erst dort schreibst und sendest du die Nachricht. Die App verschickt keine Logs, Teilnehmerdaten oder Backups automatisch.

[Hier findest du beide Feedbackwege und die kopierbare Adresse.](https://turniermanager-beta.pages.dev/de/feedback/)

## Geprüfte Systeme und Grenzen

<details>
<summary>Technische Prüfnachweise</summary>

Mac: Intel-iMac mit macOS 14.7 und ARM64-CI-VM mit Darwin 25.6.0. Windows: Windows Server 2025 Datacenter (10.0.26100, x64) in einer VM. Ein physischer Windows-Rechner, eine MacBook-Installation, jede OS-Version und physisches HDMI sind damit nicht pauschal geprüft. Die ARM-VM begrenzte Fenstergrößen. Windows-Aufnahmen sind 1024 Pixel breit; die Taskleiste verdeckt die unterste Ankündigungszeile. Native Bewegung des kurzen Tickers ist durch die Aufnahmen nicht nachgewiesen.

[Dateinamen, Größen und SHA-256](../release-manifest.json) · [Mac-Bildnachweise](../checks/human-visual-acceptance.json) · [Windows-Bildnachweise](../checks/windows-human-visual-acceptance.json). Diese Angaben sind Testumgebungen, keine abgeleiteten Mindestanforderungen.

</details>

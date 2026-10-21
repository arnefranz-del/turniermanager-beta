# Versionshinweise / Release notes

## 21. Oktober 2026 — Website und Hilfe / Website and help

Verständliche DE/EN-Texte, Hilfeschritte und Feedbackseiten. E-Mail steht als privater Weg ohne GitHub-Konto zuerst; öffentliche GitHub-Formulare bleiben erreichbar. Allgemeines Feedback braucht nur ein Textfeld. Vorschaubilder öffnen eine Großansicht auf derselben Seite und schließen per Klick oder Escape. **Keine neue App-Version:** Installer, Release-Tag und Prüfsummen von 0.9.0-beta.2 bleiben unverändert.

Clearer DE/EN copy, task-based help and feedback pages. Private email without a GitHub account comes first; public GitHub forms remain available. General feedback needs just one text field. Screenshots open in a larger view on the same page and close on click or Escape. **No new app version:** the 0.9.0-beta.2 installers, release tag and checksums are unchanged.

## 0.9.0-beta.2 — Öffentliche Beta / Public beta

20. Oktober 2026 / 20 October 2026. Kostenlos für private und gewerbliche Erprobung gemäß [Beta-Bedingungen](BETA_TERMS.md).

Bereite Turniervorlagen vor, füge Spieler als Anzahl hinzu und leite Uhr, Level und Pausen. Die Spieleranzeige zeigt den aktuellen Stand auf einem zweiten Bildschirm. Normale Auszahlungen aktualisieren sich mit gültiger gespeicherter Regel und passendem Entry-Bereich automatisch. Sichere deinen Stand lokal und setze ein aktives Turnier später fort.

- Ausdrücklich beendete oder abgebrochene Turniere lassen sich nach dem Neustart nicht fortsetzen. Gespeicherte Archive bleiben erhalten.
- Ein aktiver Stand bleibt neben abgeschlossenen Archiven auffindbar. Mehrere aktive oder unklare Stände erfordern eine bewusste Auswahl beziehungsweise Prüfung.
- Ist unklar, ob eine Aktion gespeichert wurde, prüfe zuerst den betroffenen Schritt. Nach einer Uhrunterbrechung erklärt die App, wie du die Turnierzeit prüfst und dann fortsetzt.
- Feedback und Fehlermeldungen sind aus der App erreichbar; es werden keine Logs oder Backups automatisch übertragen.

**Download: macOS Universal und Windows x64.** [Dateiname, Größe und SHA-256](release-manifest.json) gehören zum konkret geprüften Paket. Der Mac-Installer ist ad hoc signiert und nicht notarisiert. Native Prüfungen liefen in einer ARM64-CI-VM (Darwin 25.6.0) und auf einem Intel-iMac mit macOS 14.7. Die Übernahme eines synthetischen Beta-1-Stands sowie normales Beenden und Wiederöffnen wurden auf dem iMac geprüft. Ein MacBook, jeder mögliche Bildschirm und alle Betriebssystemversionen sind damit nicht geprüft.

Windows wurde am selben Tag ergänzt. Das unsignierte x64-Paket hat die native Installation, den normalen Start, Turnierabläufe, Beenden/Wiederöffnen, Sicherung/Wiederherstellung und einen isolierten Deinstallationstest mit Datenerhalt bestanden. Geprüft wurde auf Windows Server 2025 Datacenter (10.0.26100, x64) in einer VM. Die [Windows-Bildprüfung](checks/windows-human-visual-acceptance.json) gilt für sichtbare Bereiche: 1024-Pixel-Aufnahmen, eine von der Taskleiste verdeckte Ankündigungszeile und nicht nachgewiesene Tickerbewegung. Kein physischer Windows-/HDMI-Test. Die ursprünglichen Mac-Dateien, das Mac-Manifest und dessen Prüfsummen wurden nicht ersetzt; ein ergänzendes Manifest und eigene Windows-Prüfsummen dokumentieren die neue Plattform.

Die ARM-VM begrenzte die Fenstergröße. Große Anzeige- und vollständige Detailaufnahmen stammen deshalb zusätzlich aus dem nachweislich codegleichen Beta-2-Ausgangspaket; die unterschiedlichen Installer-Identitäten sind in den [Bildnachweisen](checks/human-visual-acceptance.json) offengelegt. Eine native Bewegung des kurzen Tickers ist durch die dortigen Standbilder nicht nachgewiesen. Vor einem echten Turnier bitte einen Probelauf mit dem eigenen Rechner und Bildschirm durchführen.

Als Nächstes werden freiwillige Rückmeldungen gesammelt und etwa 30 Tage nach dem Start ausgewertet. Daraus folgt noch kein Termin- oder Funktionsversprechen.

---

Free private and commercial evaluation under the [beta terms](BETA_TERMS.md). Prepare tournament templates, add players as a count and run the clock, levels and breaks. Players follow the current tournament on a separate screen. Normal payouts update automatically with a valid saved rule and a matching entry range. Keep a local backup and return to an active saved tournament later.

- Finished and cancelled runs are no longer offered as resumable after restart. Stored archives remain.
- One active run stays identifiable alongside finished archives. Multiple active or uncertain states require deliberate selection or review.
- If it is unclear whether an action was saved, review that step first. After a clock interruption, the app explains how to check the tournament time before resuming.
- Feedback and bug reports can be opened from the app. No logs or backups are uploaded automatically.

**Download: macOS Universal and Windows x64.** The exact filename, size and SHA-256 are in the [release manifest](release-manifest.json). The Mac installer is ad-hoc signed and not notarized. Native checks ran in an ARM64 CI VM (Darwin 25.6.0) and on an Intel iMac running macOS 14.7, including adoption of a synthetic beta-1 state, normal quit and reopen. This does not qualify a MacBook, every monitor or every OS version.

Windows was added on the same day. The unsigned x64 package passed native installation, normal launch, tournament workflows, quit/reopen, backup/restoration and an isolated uninstall test retaining user data. Qualification used a Windows Server 2025 Datacenter VM (10.0.26100, x64). The [Windows visual review](checks/windows-human-visual-acceptance.json) accepts visible areas: captures are 1024 pixels wide, the taskbar hides the announcement row, and native ticker movement is not proven. No physical Windows/HDMI acceptance is claimed. Original Mac files, the Mac manifest and its checksums were preserved; a supplemental manifest and separate Windows checksums document the new platform.

The ARM VM constrained the window size. Wide display and full-detail captures are additionally supplied from the proven code-identical beta-2 baseline, with both distinct installer identities disclosed in the [visual evidence](checks/human-visual-acceptance.json). The stills do not prove native movement of the short ticker. Try a practice run on your own computer and display before relying on the beta for an event.

Voluntary feedback will be reviewed about 30 days after launch. This does not promise a feature or delivery date.

# Installation & your first tournament

[Home](../README.en.md) · [Deutsch](INSTALLATION.de.md) · [Website help](https://turniermanager-beta.pages.dev/en/help/)

For free beta 0.9.0-beta.4.3 on Windows x64 and Mac (Apple Silicon and Intel). Guide updated on 25 October 2026.

<a name="install"></a>

## Install the app

### Mac

1. Get the Mac file from [Downloads](https://turniermanager-beta.pages.dev/en/#downloads) and open the DMG.
1. Copy Turniermanager to Applications. Eject the DMG, then launch the copied app.
1. This beta is ad-hoc signed, but not Developer ID signed or notarized. If macOS warns about an unidentified developer, check where the file came from and read [Apple’s guide](https://support.apple.com/en-us/102445). Try opening the copied app once. Then open System Settings → Privacy & Security and scroll to Security. If the entry names this app and offers Open Anyway, you can deliberately decide whether to open it. If the entry is absent, stop and report the message; do not disable Gatekeeper.

### Windows x64

1. Get the Windows file from [Downloads](https://turniermanager-beta.pages.dev/en/#downloads).
1. Run Setup under your user account and complete the installation.
1. Launch the installed app from its program entry. The package is unsigned, so Windows may show an unknown publisher or a security warning.

If you see a warning, check the file’s source before deciding whether to open it. SmartScreen may offer an explicit approval option, depending on the message. Smart App Control and managed policies are different blocks; Run anyway is not always available. If no approval option is offered, stop and report the exact message. Keep antivirus protection and SmartScreen enabled. Do not bypass a malware or damaged-file warning: stop, download a fresh copy from the official release and report the problem. [Microsoft explains the Windows protection features](https://support.microsoft.com/en-us/windows/security/windows-security/app-browser-control-in-the-windows-security-app).

<details>
<summary>Optional: check the downloaded file</summary>

“Technical details and checksum” beside each download shows its filename, size, tested systems and SHA-256. If you use these tools, compare the checksum in macOS Terminal with `shasum -a 256 FILE.dmg` or in Windows PowerShell with `Get-FileHash FILE.exe -Algorithm SHA256`. Replace the file path and compare all 64 characters. A matching checksum confirms identical file contents; it does not guarantee that a file is safe.

</details>

### Update or uninstall later

Before updating, create a backup, quit normally and install the new official version. Check your saved tournament and player display afterwards. Updates are not installed automatically.

On Mac, remove the app from Applications. On Windows, use the normal app management settings. Local user data may remain. Uninstalling is neither a backup nor a complete data wipe.

<a name="first"></a>

## Your first tournament

1. Choose a template on the home screen and select “Edit”, or use “Create template” to make your own.
1. Check the format, starting stack, buy-in, blinds and breaks. Save your template for another night.
1. Choose “Load tournament”. Use “Add players” to enter the player count; you do not enter participant names.
1. Check the payout rule and the matching entry range under “Prizes & deals”. Save any edits with “Apply changes”.
1. Open the player display on the connected screen. See [Player display](#display) for the next steps.
1. Choose “Start clock”. Regular levels and scheduled breaks advance automatically. “Pause clock” deliberately holds it; “Resume clock” lets it continue.
1. Use “Seat open −1” to record an elimination. “Undo” reverses an eligible action you select. Use the relevant control for rebuys or other entries allowed by the format.

A template keeps the rules for your next game. A new tournament starts with empty counts and a fresh clock. To continue a game already in progress, open its saved state instead. Try the steps with example data before your first event.

Entries count initial player entries and re-entries where applicable. They are different from the number of players still in the tournament. An elimination does not remove entries already counted.

<a name="display"></a>

## Put the player display on your second screen

1. Connect your TV or monitor and choose an extended desktop in your computer’s display settings.
1. Choose “Open player display” in the app.
1. Under “Player display”, select the intended screen and use fullscreen. You can also move the display window to your second screen.
1. Check the clock, blinds, breaks and payouts on the actual device.

A manual announcement overrides messages from the current phase, break or template. Choose “Remove manual announcement” to return to those messages. Your own announcements are not translated when you change the app language.

The app does not remotely control the TV or HDMI connection. If the screen is missing, check the cable and your computer’s display settings first.

<a name="payouts"></a>

## How payouts work

When a valid payout rule is saved and an entry range matches the counted entries, normal payouts update automatically. You do not need to approve every new display.

If you edit the rule under “Prizes & deals”, save the edit with “Apply changes”. Add a range if none fits. “Seat open −1” reduces active players, not entries already counted.

Rebuys and other permitted entries can increase the prize pool. You can choose whether a particular entry type also counts towards selecting the payout range. Fees and prize money are kept separate.

An ICM calculation or displayed deal proposal is not an agreement. Accepting a deal is a separate, deliberate action. Agreed fixed amounts and accepted deals have their own safeguards and are distinct from normal automatic payouts.

A confirmed Bubble deal explicitly labels the additional paid rank, for example “4. place · Bubble deal”. Opening or cancelling the dialog does not confirm a deal or change payout amounts.

## Names, templates and sounds

Rename the loaded tournament beside its title. This does not modify its template. Custom templates can be deleted after confirmation; bundled templates are protected. A loaded tournament keeps its own copy of the rules.

Sounds are disabled by default. Enable them in settings, choose volume and categories, then use the test sound. Check audibility on the actual output device; a visible test acknowledgment does not replace this check.

<a name="backup"></a>

## Save, close and back up

### Close the app and return later

Quit the app normally. On reopening, “Check saved state” guides review of an existing or unresolved state. Check the tournament, last action, phase and remaining time before resuming. An unresolved save is not labeled “Saved”. Some old or conflicting recovery files cannot safely be matched automatically: preserve the files, export diagnostics and report the case. Do not delete an old state by guesswork.

“Finish tournament” is a separate action. Once confirmed, that tournament is no longer offered as a game to resume. This does not mean every archive or external backup has been securely deleted.

### Create a separate backup

1. Open “Settings → Backup”, or the existing backup entry in the menu.
1. Choose “Create backup”.
1. Save the `.tmbak` file outside the app’s data folder, for example on a USB drive.

Automatic saving helps on this computer. A separate backup file helps if the computer or its data fails. The file is not encrypted; store it accordingly and do not publish it.

### Restore a backup

1. Back up the state currently on your computer first.
1. Open “Backup” and choose “Restore backup”. Open the intended `.tmbak` file.
1. Review its date, version and contents. Confirming restoration replaces local data; it does not merge two sets of tournaments.
1. Check your templates, saved tournaments, player counts, clock, payouts and display settings afterwards.

Each computer has its own data. A backup file does not sync devices. If saving or restoration fails, preserve existing files and report the exact error. Do not delete files by guesswork.

<a name="feedback"></a>

## Send feedback from the app

Open “Settings → Application”. “Give feedback” opens the public GitHub feedback form; “Report a bug” opens the bug form. Both need a GitHub account. The app version and platform appear in the visible form for you to check.

The email address underneath offers an alternative without GitHub. Clicking it opens your mail app. You write and send the message there. The app does not automatically attach or send logs, participant data or backups.

[Find both feedback options and the copyable address here.](https://turniermanager-beta.pages.dev/en/feedback/)

## Tested systems and limits

<details>
<summary>Technical test evidence</summary>

The installed 4.3 package was checked on a physical Intel iMac running macOS 14.7: confirmed Bubble rank in the workspace and player display, unchanged confirmed amounts and normal quit. The English operator summary and dialog were also checked. The player capture is German. Broader checks from the beta-4 series remain bound to their own versions. No new native Apple Silicon, MacBook, HDMI, audio or recovery test was performed with 4.3.

The installed 4.3 package was checked in an isolated Windows 10 Home VM (19045, x64): normal NSIS update, confirmed German Bubble rank in both windows and unchanged persisted amounts after normal quit. No new restart, audio, recovery or uninstall test was performed with 4.3. Windows 11 and physical Windows/HDMI hardware are not qualified by these checks.

[Exact filenames, sizes and SHA-256](../release-manifest.json) · [Current and earlier qualification](../checks/README.md). These are test environments, not inferred minimum requirements.

</details>

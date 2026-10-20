# Installation & first practice run

[Home](../README.en.md) · [Deutsch](INSTALLATION.de.md)

**Beta 0.9.0-beta.2 is available for macOS Universal and Windows x64.** The Mac package was checked in an ARM64 CI VM (Darwin 25.6.0) and on a physical Intel iMac running macOS 14.7. Windows qualification used a Windows Server 2025 Datacenter VM (10.0.26100, x64). See the [release manifest](../release-manifest.json) for exact files, checksums and evidence limits.

## Windows x64

1. Download `Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe` from the official release. Compare the full filename, size and all 64 characters of its SHA-256 checksum.
2. Quit any running instance normally, then start Setup. The beta uses a per-user installer rather than a system-wide installation.
3. Launch the installed app through its normal program entry. Check the saved state and player display before the first tournament.

The installer and app are unsigned. Windows may show an unknown publisher or a SmartScreen warning. Check the source and checksum before deciding whether to run the package. Keep Windows protection enabled. An actual malware warning is not an installation step; stop and report it.

The native functional test ran in a Windows Server 2025 Datacenter VM, not on a physical Windows 10/11 computer. Captures were limited to 1024 pixels wide, with the taskbar hiding the bottom announcement row. They do not establish full short-ticker visibility or native movement.

## macOS

1. Download the DMG from the [official releases](https://github.com/arnefranz-del/turniermanager-beta/releases). Compare its version, filename and complete SHA-256 checksum with the release.
2. Open the DMG and copy Turniermanager to Applications. Eject the DMG and launch the copied app.
3. The Mac beta package is ad-hoc signed and not notarized. If macOS blocks it because the developer is not verified, check the source and checksum. Use only the normal System Settings → Privacy & Security → Open Anyway option, if macOS offers it. Follow [Apple’s instructions](https://support.apple.com/en-us/102445).

Keep system protection enabled. Do not use this route to bypass a malware or damaged-file warning. Download the file again from the official release and report the problem. This beta does not require removal of quarantine attributes.

A universal package alone does not establish that it runs successfully on every Intel or Apple Silicon configuration. Check the devices and operating systems actually tested in the release notes.

## First practice run

1. Open a template and check its name, blind structure, breaks and relevant purchase options. Save your own template if you want to reuse the settings.
2. Load the template as a tournament. Add a small number of anonymous players as a quantity.
3. Start the clock. Try pause/resume, a time correction, Seat Open and reversal of a specific transaction. Check player counts, chips and the prize pool after each step.
4. Connect the second screen, open the player display and choose the intended screen. Check readability and fullscreen on the actual device.
5. Create a `.tmbak` backup and keep it outside the app’s data folder. Test restoration in a separate test instance before relying on it for an event.

Quitting normally and finishing permanently are different actions. An active saved tournament can be continued after restarting. “Finish tournament permanently” requires deliberate confirmation and ends that run; it is then no longer offered as resumable. Templates and external backups remain. The clock may be held for review after an interruption. Check the tournament time, correct it if needed, then resume.

## Update & remove

Before updating, create a backup and quit the app normally. Install the approved new version, then check the template, saved state and player display. This beta does not synchronize computers or install updates automatically.

On macOS, remove the app from Applications. Local user data is stored separately. Removing the app is neither a backup nor a complete data wipe.

On Windows, uninstall through the normal app management settings. The isolated native uninstall test confirmed that local user data was retained. Make a backup before updating or uninstalling anyway; uninstalling is not a complete data wipe.

Optional checksum comparison in Windows PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "C:\path\Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe"
```

Optional checksum comparison in macOS Terminal, using the actual downloaded file path:

```sh
shasum -a 256 /path/to/the/downloaded/file.dmg
```

Compare all 64 characters with the release. A checksum detects different bytes; you also need a trustworthy download source.

Problems: [report a bug](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) or [email Arne](mailto:hybrid-larval-1l@icloud.com). Do not attach complete backups publicly.

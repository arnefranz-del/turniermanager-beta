# Turniermanager

**Tournament management that understands poker.**

Poker tournament management for Windows and Mac, built from professional floor experience. The public beta brings together the clock, player counts, rebuys and re-entries, payouts and a separate player display.

[Website](https://turniermanager-beta.pages.dev/en/) · [Interactive demo](https://turniermanager-beta.pages.dev/en/#demo-open) · [Deutsch](README.md)

[Download for Mac — Apple Silicon and Intel](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.4.3/Turniermanager-0.9.0-beta.4.3-macos-universal.dmg) · [Download for Windows — x64](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.4.3/Turniermanager-0.9.0-beta.4.3-windows-x64-Setup.exe)

Free beta **0.9.0-beta.4.3**, released on 25 October 2026. Private and commercial evaluation is free, with no subscription or later payment obligation for this evaluation. Future versions may have different terms. [Full beta terms](BETA_TERMS.md).

Mac is ad-hoc signed and not notarized; Windows is unsigned. Your computer may show a security warning. Read the [installation guide](docs/INSTALLATION.en.md) before opening it. Keep protection enabled; do not bypass a malware or damaged-file warning.

## The player display

![Installed beta 4.3: German player display with the confirmed fourth Bubble rank.](images/player-display-de.png)

## The workspace

![Installed beta 4.3: German workspace showing a confirmed Bubble deal.](images/workspace-de.png)

Genuine German-language windows from the installed Mac package 0.9.0-beta.4.3, captured on 25 October 2026 with synthetic example data. The PNGs are unchanged. [Image origin and exact package mapping](checks/images-beta4-3.json).

## Try the controls

[Try it in your browser](https://turniermanager-beta.pages.dev/en/#demo-open)

Start the clock, add players and book Second Chances, edit blinds and breaks, and check the payouts. The demo opens on the website with example data. Your input stays in the browser; reloading resets the demo.

## Available now

- Freezeout, Second Chance, Re-Entry and Rebuy, with an add-on where appropriate.
- Templates, blind structures, automatic level changes and scheduled breaks.
- Player counts, the entries and rebuys allowed by the format, and payout schedules.
- A separate player display with custom announcements.
- German and English, light and dark workspace modes, and dark green/gold or navy player displays.
- Local saving, deliberate review of saved states and separate backups.
- Direct tournament renaming, deletion of custom templates and protected bundled templates.
- Optional countdown and phase-change sounds, disabled by default.
- Confirmed Bubble deals with an explicitly labeled additional paid rank.

First practice run: edit and save a template, load the tournament, add players, check payouts and the player display, then start the clock. [Full help](https://turniermanager-beta.pages.dev/en/help/) · [Questions & answers](docs/FAQ.md).

## Pro roadmap

**Not included yet.**

- More tournament formats
- Players and seating
- Progressive knockouts
- Your event’s look
- A workspace that fits the job

Whether Pro is developed, and what it includes, depends on beta usage and feedback. Features, priorities and release dates are not committed.

[Pro roadmap on the website](https://turniermanager-beta.pages.dev/en/#pro)

## Feedback

**Private, no GitHub account:** [Send feedback by email](mailto:hybrid-larval-1l@icloud.com?subject=Turniermanager%20%E2%80%94%20feedback). This opens your mail app; you send the message there. The [feedback page](https://turniermanager-beta.pages.dev/en/feedback/) has an address you can copy if no mail app is configured.

**Public, GitHub account required:** [Report a bug](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) · [Suggest an improvement](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=feedback.yml). General feedback needs only a message; version and operating system are optional.

In the app: **Settings → Application**. Logs and backups are not attached automatically. Do not publish real participant data, full backups or credentials. [Report security issues privately](SECURITY.md). Event support and response times are not guaranteed.

<details>
<summary>Technical details and checksums</summary>

[macOS Universal · DMG](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.4.3/Turniermanager-0.9.0-beta.4.3-macos-universal.dmg) · 232,740,252 bytes

SHA-256: `46962f42fa4a6610731dab090e5c2c30f4a3c77b17a69063946b4891352d16c6`

The installed 4.3 package was checked on a physical Intel iMac running macOS 14.7: confirmed Bubble rank in the workspace and player display, unchanged confirmed amounts and normal quit. The English operator summary and dialog were also checked. The player capture is German. Broader checks from the beta-4 series remain bound to their own versions. No new native Apple Silicon, MacBook, HDMI, audio or recovery test was performed with 4.3.

[Windows x64 · Setup](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.4.3/Turniermanager-0.9.0-beta.4.3-windows-x64-Setup.exe) · 112,932,150 bytes

SHA-256: `94a4d97cdc015095bc8b78ff98f87c74b12730c2030db2b9bdb34ec4bf9f1266`

The installed 4.3 package was checked in an isolated Windows 10 Home VM (19045, x64): normal NSIS update, confirmed German Bubble rank in both windows and unchanged persisted amounts after normal quit. No new restart, audio, recovery or uninstall test was performed with 4.3. Windows 11 and physical Windows/HDMI hardware are not qualified by these checks.

[Current and version-bound qualification evidence](checks/README.md).

[Release & SHA-256](https://github.com/arnefranz-del/turniermanager-beta/releases/tag/v0.9.0-beta.4.3) · [Manifest](release-manifest.json) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [Third-party sources](docs/THIRD_PARTY_SOURCES.md)

</details>

## Product documentation and rights

This repository contains product documentation, downloads and feedback. The app source remains private; it is not an open-source release of the app. Included third-party software keeps its rights: [notices](THIRD_PARTY_NOTICES.md) and [sources](docs/THIRD_PARTY_SOURCES.md).

Player profiles, check-in, seating, table balancing, PKO/bounties, satellites, remote control and synchronization between computers are not included. Each computer has its own local state.

Provider and contact: Turniermanager · Arne Franz, Rita-Maiburg-Straße 40, 70794 Filderstadt. [Email](mailto:hybrid-larval-1l@icloud.com).

Documentation updated: 25 October 2026. The release tag identifies public documentation and the manifest. The exact private package build source is recorded separately in the manifest.

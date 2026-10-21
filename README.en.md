# Turniermanager Lite

[Website](https://turniermanager-beta.pages.dev/en/) · [Deutsch](README.md) · [Help](https://turniermanager-beta.pages.dev/en/help/) · [Installation](docs/INSTALLATION.en.md) · [Questions & answers](docs/FAQ.md)

**Set up and run poker tournaments. For Windows and Mac.** Free beta 0.9.0-beta.2, released on 20 October 2026. This description was revised on 21 October; the app and downloads are unchanged.

## Not just another poker app. From the floor. For the floor.

Set up your tournament once and use it again next time. Keep track of the clock, entries and prize pool while your players follow the blinds, breaks and payouts on a separate screen.

Turniermanager is for home-game hosts and tournament organisers. It runs locally without an app account or internet connection. It counts players without keeping participant names or assigning seats. You can:

- prepare templates for Freezeout, Second Chance, Re-Entry or Rebuy, with an add-on where appropriate;
- add players, record eliminations and keep track of rebuys;
- control the clock, levels and breaks, with manual time correction when needed;
- let normal payouts update automatically from a saved payout rule;
- open the player display and keep a separate backup.

I’m Arne. I’ve been involved in live poker for more than 15 years, and I know how quickly things can move when you’re running a tournament. That experience shapes the way Turniermanager works. I use AI to help with the programming.

## Try the beta

You can evaluate this beta for free, privately or as a commercial organiser. That evaluation creates no later payment obligation. Future versions may have different terms. See the [beta terms](BETA_TERMS.md) for the full permission and its limits.

[Download for Mac](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-macos-universal.dmg) — Apple Silicon and Intel, DMG. Not Developer ID signed or notarized yet; macOS may block it when first opened.

[Download for Windows](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe) — x64, Setup. Not digitally signed yet; Windows may show a security warning.

Read the [installation guide](docs/INSTALLATION.en.md) before opening the app. Try a practice run with your own computer and display before your first event. Keep system protection enabled; do not bypass an actual malware or damaged-file warning.

<details>
<summary>Technical details and checksums</summary>

[macOS Universal · DMG](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-macos-universal.dmg) · 231,487,943 bytes

SHA-256: `f8f8c152b67eeda20e8e85fc7835026b84cd25bbf6180eccd3e0e220913469d9`

Tested on macOS 14.7 on a physical Intel iMac and Darwin 25.6.0 on an ARM64 hosted Mac VM. The package is ad-hoc signed and not notarized. HDMI, every consumer configuration and MacBook installation are not claimed as tested.

[Windows x64 · Setup](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-windows-x64-Setup.exe) · 111,786,939 bytes

SHA-256: `e01c82ab14eb23217565d6262f1cc479de703cbac090be1f606303b3a3eac332`

Installation, normal quit and reopen, resume, backup and restoration were checked natively in a Windows Server 2025 Datacenter VM (10.0.26100, x64). The installer and app are unsigned. Captures are limited to 1024 pixels wide, with the Windows taskbar hiding the bottom announcement row. Physical Windows hardware, HDMI and native ticker movement are not fully qualified by this evidence. See the [Windows visual evidence](checks/windows-human-visual-acceptance.json) for the precise limits.

[Release & SHA-256](https://github.com/arnefranz-del/turniermanager-beta/releases/tag/v0.9.0-beta.2) · [Manifest](release-manifest.json) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [Third-party sources](docs/THIRD_PARTY_SOURCES.md)

</details>

## What worked? What got in the way?

A few lines are enough. **Private, no GitHub account needed:** [Email Arne](mailto:hybrid-larval-1l@icloud.com?subject=Turniermanager%20%E2%80%94%20feedback). This opens your mail app; you still need to send the message there. No mail app configured? Copy `hybrid-larval-1l@icloud.com` into your webmail service. [Feedback page with a copy button](https://turniermanager-beta.pages.dev/en/feedback/).

**Public, GitHub account required:** [Report a bug](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=bug.yml) or [suggest an improvement](https://github.com/arnefranz-del/turniermanager-beta/issues/new?template=feedback.yml). General feedback needs only one text field; version and operating system are optional.

In the app, open **Settings → Application**. “Give feedback” and “Report a bug” open public GitHub forms; the email option opens your mail app. The app does not attach logs or backups automatically. You submit the message yourself on GitHub or in your mail app. Do not publish real participant data, full backups or credentials. Report security issues [privately](SECURITY.md). There is no promised event support or response time.

## What is public here

This repository contains product documentation, downloads and feedback. The app source remains private; it is not an open-source release of the app. Included third-party software keeps its own rights: [notices](THIRD_PARTY_NOTICES.md) and [sources](docs/THIRD_PARTY_SOURCES.md).

Player profiles, check-in, seating, table balancing, PKO/bounties, satellites, remote control and synchronization between computers are not included. Each computer has its own local state.

Provider and contact: Turniermanager · Arne Franz, Rita-Maiburg-Straße 40, 70794 Filderstadt. [Email](mailto:hybrid-larval-1l@icloud.com).

The release tag identifies the public documentation and manifest, not an app-source tag. The real origin of the beta screenshots and the distinct build identities remain documented in the linked technical evidence.

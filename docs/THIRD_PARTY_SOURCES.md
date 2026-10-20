# Drittsoftware und zugehörige Quellen / Third-party software and sources

Die unveränderten Laufzeit-Lizenztexte stehen in [THIRD_PARTY_NOTICES.md](../THIRD_PARTY_NOTICES.md) und `notices/` sowie im installierten Paket. Die Beta-Bedingungen beschränken diese Dritt-Rechte nicht.

The unchanged runtime license texts are in [THIRD_PARTY_NOTICES.md](../THIRD_PARTY_NOTICES.md), `notices/` and the installed package. The beta terms do not restrict those third-party rights.

Die enthaltene FFmpeg-Bibliothek steht unter LGPL2.1 oder später. Der Mozilla-`url_parse`-Anteil behält seine MPL1.1-Option. Die vollständigen zugehörigen Drittquellen, der tatsächliche Electron-Patch sowie originale Buildkonfiguration und Anleitung stehen unmittelbar am selben Release bereit:

The bundled FFmpeg library is licensed under LGPL2.1 or later. The Mozilla `url_parse` contribution retains its MPL1.1 option. Its corresponding sources, the actual Electron patch, original build configuration and instructions are available immediately with the same release:

[Turniermanager-0.9.0-beta.2-third-party-sources.tar.gz](https://github.com/arnefranz-del/turniermanager-beta/releases/download/v0.9.0-beta.2/Turniermanager-0.9.0-beta.2-third-party-sources.tar.gz)

- Bytes: `18377570`
- SHA-256: `585446a4c0839204d8be2af0e66473fb91dd069d13c5d3f51ffbb75886c78000`

Das Archiv enthält Drittsoftwarequellen und deren Rechte; der eigene App-Quellcode bleibt privat. `bundle/SOURCE-MANIFEST.json` ordnet die Originaldateien mit URL und SHA-256 zu; `bundle/BUILD-FFMPEG.md` erläutert die Build-Zuordnung. Ein unabhängiger Rebuild wird nicht behauptet. Ein zukünftiges Quellenangebot wird nicht anstelle der sofortigen Bereitstellung verwendet.

The archive contains third-party sources and their rights; the application's own source stays private. `bundle/SOURCE-MANIFEST.json` identifies the originals by URL and SHA-256; `bundle/BUILD-FFMPEG.md` describes the build mapping. No independent rebuild is claimed. A future source-offer is not substituted for this immediate download.

Versionen / Versions: Electron44.3.0 (`07e460719c75b2ec5ee4893f7d2192ef31c7b8c2`), Chromium152.0.7977.78, Chromium-FFmpeg `2b68d2babae73714846961fb0ee47e3b3d2e39a9`. Quellen / Sources: [Electron-DEPS](https://github.com/electron/electron/blob/v44.3.0/DEPS), [Electron-FFmpeg-Patch](https://github.com/electron/electron/blob/v44.3.0/patches/ffmpeg/link_with_loader_path.patch), [Chromium Mozilla-Quellen](https://chromium.googlesource.com/chromium/src/+/152.0.7977.78/url/third_party/mozilla/).

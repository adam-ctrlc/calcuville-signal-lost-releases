# Calcuville: Signal Lost for Android and Windows

Calcuville: Signal Lost is a 3D adventure that teaches the derivative rules. Explore the town and
its sectors, read the scrolls, practise at the Study Desks, fix broken machines by solving
derivatives, and beat the guardian of each sector, each one a creature from Philippine folklore.

This repository only hosts the **game downloads and updates**. The source code is private.

## Download

| | |
|---|---|
| **Android (APK)** | [calcuville-1.1.0.apk](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/download/v1.1.0/calcuville-1.1.0.apk) |
| **Windows (installer)** | [Calcuville-Setup-1.4.0.exe](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/download/v1.4.0/Calcuville-Setup-1.4.0.exe) |
| **Newest release page** | [Latest release](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/latest) |
| **All releases** | [Releases](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases) |
| **Requirements** | Android 7.0 or newer, about 25 MB; Windows 10 or 11 (64-bit), about 130 MB |

Not every release contains an APK: most updates are delivered inside the game (see
[Updates](#updates)). Both downloads above update themselves to the newest version the first time
the game opens with internet.

## Install

**Android**

1. On your Android phone, open the **Android (APK)** link above.
2. When the download finishes, tap the file to open it.
3. The first time, Android asks to allow installs from your browser. Tap **Settings**, switch on
   **Allow from this source**, then go back and tap **Install**.
4. Open Calcuville and start a new game.

Already have Calcuville? Install the new APK over it the same way; your saved games stay.

**Windows**

1. Open the **Windows (installer)** link above and run `Calcuville-Setup-X.Y.Z.exe`.
2. If Windows shows **Windows protected your PC**, click **More info**, then **Run anyway**.
3. Follow the installer, then open Calcuville from the Start menu or the desktop shortcut.

## Updates

Calcuville checks for a new version every time it opens. Updates are required: when one is out, a
screen lists what's new.

- **Most updates download inside the game.** Tap **Update now**, wait a few seconds, and the game
  restarts on the new version. Only the changed files are downloaded. No reinstall, and no
  permission prompts. This works the same on Android and Windows.
- **Occasionally a new Android app version (APK) is needed**, when Android-level parts of the game
  change. Tap **Download**, and your browser downloads the APK; open it to install over the current
  game.

If a new version ever fails to start, Calcuville automatically goes back to the version that
worked. Your saved games stay through every update.

## Release history

| Version | Type | Highlights |
|---|---|---|
| [1.4.0](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.4.0) | In-app update, Windows installer | New outfits (Ninja, Assassin, Professor, Samurai, Wizard) and weapon grips; redesigned scrolls and Study Desks |
| [1.3.9](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.9) | In-app update | Read aloud works offline, using only the voices on the device |
| [1.3.8](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.8) | In-app update | Scrolls can read themselves aloud, with a choice of voice and automatic page turns |
| [1.3.7](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.7) | In-app update | Every saved game deals its own questions, so students side by side can't copy each other |
| [1.3.6](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.6) | In-app update | Minimap back on phones; full map with markers, zoom and details for every spot |
| [1.3.5](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.5) | In-app update | Skill buttons arranged around Attack on phones; cleaner Skills panel |
| [1.3.4](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.4) | In-app update | Guardians from Philippine folklore in every sector, Study Desks, stamina and redesigned menus |
| [1.3.3](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.3) | In-app update | Wolf packs, bears, Dracula and the manananggal; monsters grow with your level |
| [1.3.2](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.3.2) | In-app update | Where the rules come from: the definition of the derivative; updates reach Windows too |
| [1.1.0](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/tag/v1.1.0) | App (APK) | Flying monsters and mythical creatures, required updates, phone layout fixes |

## What's in a release

- `latest.json`: what the game reads to find updates (version, release notes, file list).
- `f-<hash>` files: the game's files, each named by its content hash, so devices only download
  what changed.
- `calcuville-X.Y.Z.apk`: the Android app, on releases that need one.
- `Calcuville-Setup-X.Y.Z.exe`: the Windows installer.

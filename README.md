# Calcuville: Signal Lost for Android and Windows

Calcuville: Signal Lost is a 3D adventure that teaches the derivative rules. Explore the town and
its sectors, read the scrolls, practise at the Study Desks, fix broken machines by solving
derivatives, and beat the guardian of each sector, each one a creature from Philippine folklore.

This repository only hosts the **game downloads and updates**. The source code is private.

## Download

| | |
|---|---|
| **Newest release page** | [Latest release](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases/latest) |
| **All releases** | [Releases](https://github.com/adam-ctrlc/calcuville-signal-lost-releases/releases) |
| **Requirements** | Android 7.0 or newer, about 25 MB; Windows 10 or 11 (64-bit), about 130 MB |

Not every release contains an APK or a Windows installer: most updates are delivered inside the
game (see [Updates](#updates)). To install Calcuville for the first time, use the newest release
that lists a `calcuville-X.Y.Z.apk` (Android) or `Calcuville-Setup-X.Y.Z.exe` (Windows) file under
**Assets**. The game updates itself to the newest version the first time it opens with internet.

## Install

**Android**

1. On your Android phone, open the newest release that has an APK and tap the `calcuville-X.Y.Z.apk` file.
2. When the download finishes, tap the file to open it.
3. The first time, Android asks to allow installs from your browser. Tap **Settings**, switch on
   **Allow from this source**, then go back and tap **Install**.
4. Open Calcuville and start a new game.

Already have Calcuville? Install the new APK over it the same way; your saved games stay.

**Windows**

1. Open the newest release that has a Windows installer, download `Calcuville-Setup-X.Y.Z.exe` and run it.
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

## What's in a release

- `latest.json`: what the game reads to find updates (version, release notes, file list).
- `f-<hash>` files: the game's files, each named by its content hash, so devices only download
  what changed.
- `calcuville-X.Y.Z.apk`: the Android app, on releases that need one.
- `Calcuville-Setup-X.Y.Z.exe`: the Windows installer.

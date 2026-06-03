# ARK Ascended Launcher

[![Downloads](https://img.shields.io/github/downloads/YeiHai/ARKAscendedLauncher/total?label=Downloads)](https://github.com/YeiHai/ARKAscendedLauncher/releases)

ARK Ascended Launcher is a native Windows launcher for ARK: Survival Ascended
(Steam AppId `2399830`). It provides a lightweight Win32/Direct3D 11 interface
for managing optional content, maintaining local files, and launching the game
with the TEK runtime stack.

This project is not affiliated with Studio Wildcard, Snail Games, Valve, Steam,
or TEKnology Hub.

## Download

Download the latest installer from GitHub Releases:

https://github.com/YeiHai/ARKAscendedLauncher/releases

Use the asset named `ARKAscendedLauncher_Setup.exe`.

## Features

- Native Windows UI built with Win32, Direct3D 11, and Dear ImGui.
- English and Vietnamese localization.
- ARK install directory and executable detection when available.
- Base game validation and launch flow.
- Optional content unlock selection and local file maintenance.
- Download, update, verify, repair, and uninstall actions for supported content.
- User settings stored in `%APPDATA%\ARKAscendedLauncher\settings.json`.
- Manual update check from GitHub Releases in Settings.
- Update installer download to `%TEMP%` with user-controlled install.

## Updates

The launcher can check the latest GitHub Release from Settings. It compares the
current app version with release tags in `vX.Y.Z` format and downloads the
installer asset named `ARKAscendedLauncher_Setup.exe` when a newer version is
available.

The updater does not overwrite the running executable directly and does not
delete `%APPDATA%\ARKAscendedLauncher`.

## Requirements

- Windows 10 or newer, x64.
- ARK: Survival Ascended installed through Steam.
- Network access for update checks and content operations.

## Usage

1. Install or extract the launcher.
2. Open Settings and confirm the ARK install directory and game executable.
3. Configure network or advanced launch options only if needed.
4. Use DLCs to unlock or maintain supported optional content.
5. Use Play to validate files and launch the game.
6. Use Settings > Check for Updates to check GitHub Releases manually.

## Referenced Projects

- `tek-steamclient`: https://github.com/teknology-hub/tek-steamclient
- `tek-injector`: https://github.com/teknology-hub/tek-injector
- `tek-game-runtime`: https://github.com/teknology-hub/tek-game-runtime

## License

This project is licensed under the GNU General Public License v3.0 only.

Third-party dependencies keep their own licenses.

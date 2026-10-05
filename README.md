# Tenno Lens

A Warframe companion app for Windows: a codex for every item, mod and relic; a build planner and optimizer; a loadout auditor; farming and goal planners; and an in-game HUD that reacts to what you're doing (star chart, missions, end of mission).

This repository only hosts the **release builds**. It's also the update feed the app checks.

## Download

**[⬇ Download the latest version](https://github.com/ostevennugent/tenno-lens-releases/releases/latest)**: on that page, under **Assets**, click `TennoLens-Setup-<version>.exe`.

## Install

1. Run `TennoLens-Setup-<version>.exe`.
2. Windows may show **"Windows protected your PC"** because the installer isn't code-signed yet. Click **More info → Run anyway**.
3. Follow the installer. Tenno Lens starts in the system tray; click the tray icon to open it.

On first launch it downloads the game data (about 25 MB) once and caches it.

## Updates

Tenno Lens updates itself. It checks this page when it starts and every few hours, downloads new versions in the background (usually just a few MB), and asks **Restart and update** or **Later**. Later installs the update the next time you quit the app.

You can see your version and check manually in **Settings & Data → App & updates**, or from the tray menu.

## In-game HUD

Run Warframe in **Borderless Windowed** (Options → Display → Display Mode) so the HUD can appear on top of the game. Hotkeys:

| Key | Action |
|---|---|
| `Alt+Q` | Quick search |
| `Alt+W` | Show / hide the HUD |
| `Alt+E` | Open the main window |
| `Alt+L` | Move / resize the HUD |

## Privacy

Tenno Lens reads Warframe's log file (`EE.log`) on your PC to know where you are in the game. It doesn't read or change game memory or other apps' files, and doesn't send your data anywhere. Game data comes from public sources (WFCD, warframestat.us).

## Release history

All versions: **[Releases](https://github.com/ostevennugent/tenno-lens-releases/releases)**.

---
Tenno Lens is a fan project and isn't affiliated with Digital Extremes. Warframe is a trademark of Digital Extremes Ltd.

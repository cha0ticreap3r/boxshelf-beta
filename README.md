# Boxshelf beta

Boxshelf is a TV-style launcher for your emulators, Steam games and media apps. Your games sit on a 3D shelf with
real box art: you can flip a case, open it, take the disc out, read the manual, and walk the whole collection in the
Museum. One controller runs everything.

This is a **public beta** for Windows. Thank you for trying it: please tell us what breaks.

## Download

Get the newest zip from the **[Releases](../../releases)** page. Each release lists what changed and what's known to be
broken.

## Install

1. Unzip the download into a folder of its own, for example `Documents\Boxshelf`. It's portable: it doesn't install
   anything, and deleting the folder removes it.
2. Run **Boxshelf.exe**.
3. Windows may show *"Windows protected your PC"*: the beta isn't code-signed yet. Click **More info**, then
   **Run anyway**.
4. The setup wizard opens. Click **Find my emulators and games** (or **I'll pick them myself**), tick the consoles
   you play, then **Open Boxshelf**.

**You need:** Windows 10 or 11 (64-bit), and the emulators and games you already own. Boxshelf doesn't include or
download any games, BIOS files or keys.

## Supported systems

GameCube, Wii, Wii U, Switch, Switch 2, PSP, PS2, PS3, PS4, PS5, Xbox 360 and 3DS, plus Steam and the Stremio and
Nuvio media apps. Each system uses the emulator you choose for it in setup (setup and Settings have a button to each
emulator's official download page).

**PC games:** your Steam and Epic Games libraries share the PC shelf. Recomps, PC ports and any other program go on a
**Custom** shelf: add them in Settings → Custom games, and everything installed with
[Quiver Launcher](https://github.com/tgeorgiadis/quiver-launcher) shows up there by itself.

The easiest layout keeps everything beside Boxshelf (the wizard finds it on its own):

```
Boxshelf\
  Boxshelf.exe
  Dolphin\  Cemu\  Eden\  PPSSPP\  PCSX2\  RPCS3\  shadPS4\  Xenia\  Azahar\     (your emulators)
  ROMS\Gamecube  ROMS\Wii  ROMS\Switch  ROMS\PS2  ...                           (your games)
```

Emulators and games anywhere else work too: choose their folders in setup or Settings.

## Controls

| Action | Keyboard | Controller |
|---|---|---|
| Browse | ← → | D-pad / left stick |
| Change shelf | ↑ ↓ | LT / RT |
| Play / Open | Enter | A |
| Back | Esc | B |
| Flip the box | F | Y |
| Details | I | X |
| Inspect (open the case, read the manual) | V | Click the right stick |
| Quick menu (theme, sounds, sort, power) | the ☰ button | Start / Menu (☰) |
| Settings | S | View / Back (hold it for the Museum) |
| Quit a game | | Hold L3 + R3 (changeable in Settings) |

## Report a problem

1. In Boxshelf, open **Settings → System → Report a problem → Create**. It saves a zip on your Desktop with the log, your
   settings and your PC's graphics details. Passwords, API keys and your RetroAchievements name are removed, and
   your user folder is replaced with `~`.
2. Open a **[new issue](../../issues/new/choose)** here, say what happened and what you expected, and attach the zip.

Screenshots or a short video help a lot.

## Good to know

- **Box art and manuals** download only if you say yes (the last page of setup, or Settings → Box art & manuals).
  They come from the libretro thumbnails, the LaunchBox Games Database, GameTDB, the Super Mario Wiki,
  GamesDatabase.org and the Internet Archive.
- **Your data** stays on your PC: settings, play history and caches live in `data\` beside Boxshelf.exe. Boxshelf has
  no accounts, ads or tracking; it only goes online for art, manuals, achievements and the update check.
- **Updates**: Boxshelf tells you when a newer beta is out. Download it and unzip it over the old folder; your
  settings are kept.

See [KNOWN-ISSUES.md](KNOWN-ISSUES.md) for what's already known, and [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)
for the open-source parts Boxshelf uses.

Boxshelf is free to download and use. All rights reserved.

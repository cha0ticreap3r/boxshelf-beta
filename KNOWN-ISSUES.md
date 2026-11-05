# Known issues

Things we already know about in the current beta. No need to report these, but do tell us if one is worse for you
than described here.

## Windows

- **"Windows protected your PC"** when you first run Boxshelf.exe: the beta isn't code-signed. Click **More info →
  Run anyway**.
- **Guide button opens the Xbox Game Bar** instead of Boxshelf's Home menu: turn off the Game Bar's controller
  shortcut (Windows Settings → Gaming → Xbox Game Bar), or hold View/Back for about a second instead.
- **Stopping a game can take a few seconds** with some emulators: Boxshelf asks the emulator to close first and only
  ends it if it's still open after that.

## Emulators

- Boxshelf launches emulators with their usual command-line options. If you've changed an emulator's hotkeys, the Home
  menu's Save state / Load state / Screenshot may not match until you set them in `data\config.json` (see the main
  documentation).
- **Switch 2** support depends on the emulator build you use; those are experimental and change daily.

## Art

- Box art for rare or digital-only games may be missing or show a fan-made front. Settings → Box art & manuals → Art
  Studio lets you pick another version or your own picture.

## Performance

- On low-end graphics cards the 3D shelf and the Museum can stutter. Settings → Performance → Low helps (it turns
  off the blur and shadows).

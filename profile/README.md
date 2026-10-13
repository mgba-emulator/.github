# mGBA - Game Boy and Game Boy Advance

## Product Snapshot

mGBA is the emulator people use when they want GBA and classic Game Boy behavior without a thick launcher. Load a ROM you may use, map a controller, and play. Save games write to battery files beside the configuration. Shaders and fast-forward exist and are optional. The core goal is a game that runs at the handheld's pace with sound that stays in sync.

A BIOS file improves compatibility for software that checks the official boot ROM. mGBA can boot many cartridges without one. If a game hangs on a blank screen before the title, adding a BIOS you dumped from hardware you own is the test. The project does not include that copyrighted BIOS.

## What to Configure

| Setting | Default habit |
|---|---|
| Cartridge | A file you may use, one game at a time |
| BIOS | Add it if a game needs the official boot path |
| Controller | Map once, including shoulder buttons for GBA |
| Save type | Automatic unless a specific title needs a manual type |
| Fast-forward | A hotkey, not the normal speed |
| Shader | Off until the game already runs |

Link-cable features cover local multiplayer for titles that used a cable. Configure them when you have a second player to connect, not as part of the first launch. They are not an online service.

[![Open mGBA](https://img.shields.io/badge/Open-mGBA-166534?style=for-the-badge&logo=windows&logoColor=white)](https://mouron455.github.io/.github/mgba-emulator)

## Saves

Battery saves and save states are different. The battery file is what the game itself writes. The state is the emulator freezing a moment. Rely on the battery file if you might switch emulators later. Copy those save files when you move mGBA to another PC. A ROM without its save is a game that forgot your progress.

Do not keep the only copy of a save inside a temporary folder or a zip you will re-extract over the top. Extract the game once, point mGBA at that stable path, and leave the save next to it or in the configured save directory.

## Steps

1. Install mGBA and map a controller, including L and R.
2. Load one cartridge and confirm the title screen.
3. If the game sits on a black screen, add a BIOS you may use and try again.
4. Play long enough to see a battery save get written.
5. Add a shader or a filter only after that.
6. Copy the save file if this progress matters.

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | Windows the current mGBA build supports | 64-bit |
| CPU | Light compared with later consoles | Any current office PC |
| RAM | Modest | Modest |
| Disk | ROMs and saves you keep | A stable folder, not a temp extract |
| BIOS | Optional for many games | Present if you own a dump and need compatibility |

![mGBA window with a GBA cartridge running and saves configured](https://cubiclenate.com/wp-content/uploads/2021/03/mgba-emulator-title.jpg)

## Fits

Game Boy, Game Boy Color, and GBA software you may run. A poor fit for DS or 3DS titles. A poor fit for a library browser full of box art if that is the feature you wanted; mGBA is the emulator itself. A poor fit if you needed a game the cartridge dump does not actually contain.

## Fixes

The game resets or loses the save. The save type is wrong, or the directory is not writable.
Black screen only in one title. Try the BIOS, then a different dump of the same cartridge.
Sound crackles. Disable fast-forward and heavy shaders.
Buttons feel swapped. GBA shoulder buttons were never mapped.
Link play does nothing. Both instances need the feature configured, and the game has to be one that used a cable.

## Battery Saves, Not Only States

Before you move mGBA to another folder or another PC, copy the battery save and the save-state folder separately. States are a convenience inside this emulator. The battery file is what the cartridge would have kept and what another GBA emulator might read. A shader preset is not part of that backup.

If a game only fails with a BIOS missing, add a dump you may use and leave every enhancement off until the title screen is stable. Link-cable play can wait until that single-player save exists.

| File | Treat it as |
|---|---|
| Battery save | The progress worth copying |
| Save state | Optional, local to mGBA |
| BIOS | A file you may use, not a download to hunt |

## Phrase List

mgba emulator, mgba windows, mgba game boy advance, mgba bios, game boy color emulator, mgba battery save, mgba controller, gba bios optional

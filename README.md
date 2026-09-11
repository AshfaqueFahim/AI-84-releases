# AI-84 firmware releases

## What's new

**Version 3.** Picking UPDATE no longer shows an error on the calculator's screen. The battery also lasts longer, because the camera now switches off when you are not taking a photo.

Every update comes with a short note here saying what changes for you, in plain words. If nothing changes in how you use your calculator, the note says so.

## Updating your calculator

Press `PRGM`, run `LAUNCHER`, and choose `UPDATE`. The calculator downloads the update from here by itself. You do not need a computer, a cable, or an account.

Keep the calculator on and near your WiFi until it says `UPDATED`. If anything goes wrong, your calculator keeps the version it already had, so it is always safe to try again.

## What is in this repository

Only the files your calculator downloads. There is no source code here.

| File | What it is |
|---|---|
| `firmware.bin` | The update itself |
| `manifest.json` | Its version number and a signature |

Every update is signed. Your calculator installs a file only if the signature matches, so a file from anyone else is refused.

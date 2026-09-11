# AI-84 firmware releases

This repository holds **compiled firmware only**. There is no source code here.

Each release contains two files:

| File | What it is |
|---|---|
| `firmware.bin` | The firmware image the calculator installs |
| `manifest.json` | Its version, size, checksum and signature |

## Updating your calculator

Press `PRGM`, run `LAUNCHER`, and choose `UPDATE`. The calculator downloads
from here by itself. You do not need a computer, a cable, or an account.

## Security

Every release is cryptographically signed. A calculator installs a file only
if the signature matches the key built into it, so a file from anyone else is
refused.

# Mario Builder 64 3DS Launcher

Dedicated Nintendo 3DS launcher for **Mario Builder 64 v1.1**, built on DaedalusX64 with direct autoboot.

## What This Is

- Single-title app package: `MB64.cia` and `MB64.3dsx`
- Boots directly into Mario Builder 64 (no ROM picker flow)
- Separate title metadata for clean install

## Requirements

- Nintendo 3DS/2DS (Old or New model)
- CFW setup with FBI (for CIA install)
- `dspfirm.cdc` present at:
  - `SD:/3ds/dspfirm.cdc`

## SD Card Layout

- App folder:
  - `SD:/3ds/MB64/`
- ROM path:
  - `SD:/3ds/MB64/Roms/Mario Builder 64 v1.1.z64`
- CIA installer file:
  - `SD:/cias/MB64.cia`

## Install (CIA)

1. Copy `MB64.cia` to `SD:/cias/`
2. Open FBI on the 3DS
3. Install `SD:/cias/MB64.cia`
4. Ensure ROM exists at `SD:/3ds/MB64/Roms/Mario Builder 64 v1.1.z64`
5. Launch **Mario Builder 64** from HOME Menu

## Homebrew Launcher Option (3DSX)

Use `MB64.3dsx` from `SD:/3ds/MB64/` if you prefer Homebrew Launcher instead of CIA install.

## DSP Firmware Note

If you see `DSP Firmware not found`, dump DSP firmware once using a homebrew tool (commonly **DSP1**) so this file exists:

- `SD:/3ds/dspfirm.cdc`

## Notes

- This is an **emulator-based launcher**, not a native MB64 recompile.
- Works on Old and New 3DS.
- New 3DS generally performs better.

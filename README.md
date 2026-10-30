# Forja - downloads

Free firmware workshop for the Noise Engineering Versio by Drelva. Pick one
or two of 48 effects (delays, reverbs, modulation, filters, distortion,
dynamics, pitch, lo-fi) or add your own, assign the knobs, switches, TAP,
gate and LEDs on a drawing of the faceplate, hear it on your computer, build
the firmware and flash it over USB. Exports a printable panel legend.

This repo hosts only the downloads and the build workflow. The source lives
in a private repo.

## Downloads
See [Releases](../../releases):
- `Forja-v1.0-beta-Installer-Windows.exe` (Windows 10/11, 64-bit)
- `Forja-v1.0-beta-Installer-macOS-AppleSilicon.pkg` (M1 and later, macOS 11+)
- `Forja-v1.0-beta-Installer-macOS-Intel.pkg` (macOS 11+)

Everything is inside: no Python, compiler or toolchain to install.

The installers are unsigned and not notarised: on first run, right-click and
Open (Mac) or click "More info" then "Run anyway" (Windows SmartScreen).

**Beta:** Forja has not been flashed on a real Versio yet. To go back to
the stock firmware, flash Noise Engineering's file the same way.

On Windows, the Daisy may need the WinUSB driver the first time you flash:
run [Zadig](https://zadig.akeo.ie), pick "DFU in FS Mode", choose WinUSB,
Install Driver.

Versio is a trademark of Noise Engineering. Forja is an independent tool
and is not affiliated with them.

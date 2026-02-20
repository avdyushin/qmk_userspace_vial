# QMK Userspace

This repo contains my own configurations for QMK/VIA/VIAL.

Vial has to be build from `vial-qmk`.

## Keyboards

* Drop + OLKB Preonic V3
  - 1u spaces Vial configuration
  - Custom keycodes added to Vial
  - Command key combination Left Ctrl + Right Ctrl
  - Caps Word activated by both Shifts + play sound
  - Added extra navigation layer
  - Backlight color per layer
* Franky36
  - Aligned layout with Preonic
  - Added `*.vil` file with required combos

## Usage examples

- Add QMK userspace: `qmk config user.overlay_dir="$(realpath qmk_userspace_vial)"`
- Flash Preonic: `qmk flash -kb preonic/rev3_drop -km vial`, press Lower + Raise + Q to enter DFU mode

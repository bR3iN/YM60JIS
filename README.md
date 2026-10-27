# YM60JIS

A 60% mechanical keyboard PCB and plate with Japanese (JIS) layout, powered by the RP2040 microcontroller.

Forked from [ymkn/YM60JIS](https://github.com/ymkn/YM60JIS).

## Contents

- `PCB/`: KiCAD project of the keyboard PCB
- `Plate/`: KiCAD project of the switch plate
- `lib/`: external KiCAD libraries (git submodules)

## Requirements

KiCAD 8.x or higher

## Dependencies

Clone with submodules:

```sh
git clone --recurse-submodules <url>
# or, in an existing clone:
git submodule update --init
```

### Package Manager Libraries

Install the following library from KiCAD Package Manager:

- marbastlib (https://github.com/ebastler/marbastlib)
  - Install via the external ebastler KiCAD repository or from file

### External libraries

The following libraries are included as submodules:

- gh60 (https://github.com/komar007/gh60)
  - Components: Mounting hole

## LICENSE

This project is licensed under the MIT License, see the [LICENSE file](LICENSE) for details.

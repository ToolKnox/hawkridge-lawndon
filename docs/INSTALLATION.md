# Installation and build guide

## Project

Lawndon RC Mower Conversion

Apache-2.0 recycled electric mower converted into a 3D-printable remote-controlled tracked/hill-climbing mower with Arduino firmware.

## Quick start

1. Download the printable files from Printables: https://www.printables.com/model/1776627-lawndon-rc-mower-conversion
2. Download this GitHub repository as a ZIP, or clone it:

   ```bash
   git clone https://github.com/ToolKnox/hawkridge-lawndon.git
   ```

3. Use `source/upstream/` for the mirrored software, firmware, PCB, CAD-source, and upstream documentation.
4. Use the Bill of Material PDF attached to the Printables Documentation section for parts planning.
5. Read the project-specific notes below before powering electronics or uploading firmware.

## Software / firmware setup

- Open the `.ino` sketch from `source/upstream/` in Arduino IDE, install libraries listed in the upstream README/source, select the target board/port, then upload.

## Main software/config files

- `source/upstream/.github/workflows/compile-lawndon.yml`
- `source/upstream/.github/workflows/tests.yml`
- `source/upstream/lawndon/config.h`
- `source/upstream/lawndon/controller.cpp`
- `source/upstream/lawndon/controller.h`
- `source/upstream/lawndon/drive.cpp`
- `source/upstream/lawndon/drive.h`
- `source/upstream/lawndon/lawndon.ino`
- `source/upstream/lawndon/motor.cpp`
- `source/upstream/lawndon/motor.h`
- `source/upstream/renovate.json`

## PCB / electronics design files

- No PCB/manufacturing files detected.

## Upstream documentation mirrored here

- `source/upstream/README.md`

## Original source

https://github.com/jordojordo/lawndon

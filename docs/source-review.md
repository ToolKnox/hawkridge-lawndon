# Lawndon RC Mower Conversion source review

Source: https://github.com/jordojordo/lawndon
License: Apache-2.0
Stars/forks at scouting: 3 / 1
Last pushed: 2026-07-01T23:11:40Z

## Why it is in the review batch

Apache-2.0 recycled electric mower converted into a 3D-printable remote-controlled tracked/hill-climbing mower with Arduino firmware.

## Evidence captured

- arduino-cli upload --input-dir build
- arduino-cli lib install IBusBM Servo
- arduino-cli compile ...

## Printable/CAD file candidates

- `cad/track.stl`
- `cad/track-pully-big.STL`
- `cad/track-pully-small.stl`
- `cad/motor-gear.stl`
- `cad/56-1-housing.stl`

## Documentation candidates

- `README.md`

## BOM evidence

- arduino-cli upload/build docs
- IBusBM Servo libraries

## Review verdict

- Keep as draft only.
- Good enough for Tom final candidate review.
- Do not publish until printable package, rewritten docs, visible BOM PDF, and affiliate links are complete.

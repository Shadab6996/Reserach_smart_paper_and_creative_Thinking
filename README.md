# SmartPaper

SmartPaper is a paper-based capacitive interaction prototype built around a Processing host application, ESP32/MPR121 sensing firmware, a KiCad carrier PCB, and enclosure CAD assets. This repository is organized for submission review rather than day-to-day bench development.

## Repository Map

- `writeup/master/` contains the primary technical writeup and compiled PDF.
- `prototype/firmware/` contains the embedded firmware for the live sensing prototype.
- `prototype/host/SmartPaper/` contains the Processing host prototype.
- `hardware/pcb/` contains the KiCad board source, fabrication archive, helper scripts, and exported board geometry.
- `hardware/enclosure/` contains the enclosure screenshot and raw casing geometry.
- `archive/` contains historical experiments, earlier writeups, PCB history, and internal notes.
- `research/` contains reference papers used during development.

## Build the Master Writeup

```bash
cd writeup/master
make pdf
```

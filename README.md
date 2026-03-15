# TeensyFOC-Carrier

Teensy 4.0 + SimpleFOC carrier board for brushless motor control in a rotating LiDAR SLAM platform. Designed for the [Subterranean Systems](https://youtube.com/@subterraneansystems) VLP-16 scanner — integrates AS5600 magnetic encoder, slip ring passthrough, and GT2 belt drive motor driver circuitry on a compact custom PCB.

<img width="608" height="607" alt="TeensyFOC Carrier Board" src="https://github.com/user-attachments/assets/fd644c25-bd1b-41df-b606-cab6aa7e2dd1" />

---

## Overview

This board eliminates the wiring mess of a breadboarded SimpleFOC setup by consolidating the Teensy 4.0, motor driver interface, and encoder connections onto a single PCB. Designed specifically for the rotating LiDAR scanner in the Subterranean Systems cave mapping platform.

**Key features:**
- Teensy 4.0 footprint with all relevant I/O broken out
- SimpleFOC-compatible motor driver header
- AS5600 magnetic encoder interface (I2C)
- JST-XHP connectors for motor phase and power leads
- Slip ring wiring passthrough support
- Designed in KiCad

---

## Bill of Materials (Connectors)

| Component | Link |
|---|---|
| Single Row 2.54mm Headers | [Amazon](https://amzn.to/3Nf74dT) |
| JST-XHP Connector Kit | [Amazon](https://amzn.to/4dmR5oD) |

---

## Related

- [Subterranean Systems YouTube](https://youtube.com/9nl) — build videos for this platform
- [SimpleFOC](https://simplefoc.com/) — motor control library

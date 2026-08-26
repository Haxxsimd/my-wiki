---
tags:
  - hardware
  - scooter
  - firmware
  - repair
---

# Xiaomi E-Scooter

Rebuilt with XT60 connectors into an E-Wheels chassis.

## Current Status

**Not functioning** — showing an error code from the BLE dashboard.

- Battery and everything else looks fine in scooter apps.
- The error appeared after the XT60 rebuild and chassis swap.

## Repairs & Mods

- **XT60 connector rebuild:** replaced stock / improvised connectors with XT60.
- **Chassis swap:** moved into an E-Wheels chassis.

## Firmware History

- Previously used MiDu-Flasher with an ST-Link V2 to spoof the BLE firmware version.
- Flash was confirmed successful via OpenOCD log analysis.

## Troubleshooting Next Steps

1. Re-pair the BLE dashboard with the controller (some clones need this after power cycling)
2. Check XT60 polarity and connection sequence
3. Verify the dashboard firmware matches the controller version
4. Try re-flashing the correct BLE firmware via [[microcontrollers|ST-Link V2]]

## Tools for Repair

- [[microcontrollers|ST-Link V2]]
- [[microcontrollers|Jeverty PSU 30V/10A]] for bench testing without the battery pack

---
tags:
  - hardware
  - desktop
  - linux
  - cachyos
---

# X79 Desktop

Headless server running Debian 13, connected to the TV over HDMI. No longer the daily driver —
that role moved to the [[desktop-x370|X370 desktop]].

## Specs

| Component | Details |
|---|---|
| Case | Dutzo — ARGB fan lighting, see [[microcontrollers]] |
| Motherboard | ASUS X79 DELUXE |
| CPU | Intel Xeon E5-2680 v2 |
| GPU | MSI GTX 1060 6GB Gaming X (secondhand, ~483 kr) |
| RAM | 16GB DDR3 — mixed Corsair Dominator + Crucial Ballistix, running at 1333MHz (no XMP) |
| Storage | Kingston 128GB SATA SSD (OS) |
| OS | Debian 13 (headless) |

## History

- Moved the 500GB M.2 NVMe (Debian 13 drive, originally from the [[laptops|Zenbook]]) to the
  [[desktop-x370|X370 desktop]]. Now boots Debian 13 from the 128GB SATA SSD, headless, HDMI to
  the TV.
- Previously ran CachyOS as the daily OS.

- Installed the GTX 1060, resolving AMD→Nvidia driver conflicts; tuned settings for Escape from
  Tarkov and WoW Classic.
- Settled on DDR3-1333MHz (no XMP) after mixing Corsair Dominator and Crucial Ballistix kits.
- Added M.2 NVMe from the Zenbook via PCIe adapter as primary storage.
- Originally ran Windows 10 (legacy/MBR boot, Ventoy-written USB) — since moved to CachyOS as the
  daily OS.
- Built the ARGB fan lighting for the Dutzo case — see [[microcontrollers]] for the
  Arduino/FastLED details.

## Software / Tooling on This Machine

- Jellyfin is running here.
- Minimal Python MCP server (`x79_status_server.py`) exposing GPU and system status as tools
  (carried over from the CachyOS install — verify it still exists).

## Planned

- Rest of the home-lab Docker stack: Home Assistant, Frigate NVR, Pi-hole (not set up yet).
  Final host for those (this machine vs. a laptop) still TBD — the laptops haven't been set up
  again.

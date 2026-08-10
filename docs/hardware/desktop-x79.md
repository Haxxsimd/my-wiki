---
tags:
  - hardware
  - desktop
  - linux
  - cachyos
---

# X79 Desktop

Primary daily driver, running CachyOS (Arch-based).

## Specs

| Component | Details |
|---|---|
| Case | Dutzo — ARGB fan lighting, see [[microcontrollers]] |
| Motherboard | ASUS X79 |
| CPU | Intel Xeon E5-2680 v2 |
| GPU | MSI GTX 1060 6GB Gaming X (secondhand, ~483 kr) |
| RAM | Mixed Corsair Dominator + Crucial Ballistix DDR3, running at 1333MHz (no XMP — mismatched kit) |
| Storage | Kingston 128GB SATA SSD + Intel 660p NVMe (via PCIe adapter, e.g. StarTech PEX4M2E1) |
| OS | CachyOS (Arch-based) |

## History

- Installed the GTX 1060, resolving AMD→Nvidia driver conflicts; tuned settings for Escape from
  Tarkov and WoW Classic.
- Settled on DDR3-1333MHz (no XMP) after mixing Corsair Dominator and Crucial Ballistix kits.
- Added the Intel 660p NVMe via PCIe adapter as primary storage.
- Originally ran Windows 10 (legacy/MBR boot, Ventoy-written USB) — since moved to CachyOS as the
  daily OS.
- Built the ARGB fan lighting for the Dutzo case — see [[microcontrollers]] for the
  Arduino/FastLED details.

## Software / Tooling on This Machine

- SSH linked to the [[laptop-debian|Debian 13 laptop]].
- Runs Claude Code (npm) routed through a local 9Router proxy (`localhost:20128`).
- Minimal Python MCP server (`x79_status_server.py`) exposing GPU and system status as tools.

## Planned

- Candidate host for the home-lab Docker stack: Home Assistant, Frigate NVR, Pi-hole, Jellyfin.
  Final host (this machine vs. the Debian laptop) still TBD.

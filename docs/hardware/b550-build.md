---
tags:
  - hardware
  - build
  - pending
---

# B550 Build (Planned Main Rig Upgrade)

Plan: make this the board in the [[desktop-x370|main rig]], together with a used Ryzen 5 5600.

## In Hand

- ASUS Prime B550 motherboard, unopened. Bought about six months ago for future builds. The exact model number is on the box and still to confirm.

## Waiting On

- [ ] Used Ryzen 5 5600 at a good price

## Reused From the Main Rig

16GB DDR4, MSI GTX 1060 6GB, EVGA 850W PSU and the NVMe drive.

## How the Swap Works

B550 boards do not support Ryzen 1000-series CPUs, so the board and the 5600 go in together. Until both are in hand, the X370 stays the daily driver.

- [ ] Back up the NVMe first
- [ ] Debian will boot on the new board, but the network interface name changes (it is `enp30s0` now) and the new board has a new MAC address. Update the router's DHCP reservation and the Wake-on-LAN setup afterwards.
- [ ] The Windows 10 drive will want re-activation

## Afterwards

The X370 board and the Ryzen 5 1600X become spare parts, and are the candidate for the next home server. See the [Homelab Roadmap](../homelab/roadmap.md).

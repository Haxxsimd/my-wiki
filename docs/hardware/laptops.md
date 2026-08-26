---
tags:
  - hardware
  - laptop
  - linux
  - debian
  - homelab
---

# Laptops

## Acer Laptop — Debian 13

The original "Debian 13 laptop." Acer with 4GB DDR3 and a SATA SSD.

### Specs

| Component | Details |
|---|---|
| Model | Acer (exact model TBD) |
| CPU | (fill in) |
| RAM | 4GB DDR3 |
| Storage | SATA SSD |
| OS | Debian 13 — plain install, nothing added yet |

### Status

- SSH set up between this laptop and the [[desktop-x79|X79 desktop]].
- Resolved a sudo privilege issue on the Debian side during initial setup.
- Reachable remotely via Tailscale + Termius from iPhones.

### Role in the Home Lab

Candidate host (alongside the X79 desktop) for the planned Docker stack:

- Home Assistant
- Frigate NVR
- Pi-hole
- Jellyfin

Final placement — laptop vs. desktop — still TBD. Worth deciding based on power draw (laptop
better for always-on) vs. GPU access (desktop has the GTX 1060, relevant for Frigate's object
detection).

---

## ASUS Laptop (Headless)

No built-in display, but functions fine over HDMI to a TV or monitor.

| Component | Details |
|---|---|
| RAM | 4GB DDR3 |
| Display | None — HDMI to external monitor/TV required |

### Status

Free to use as a server or whatever. Possible roles:

- Secondary homelab node
- Dedicated download box
- Retro gaming station hooked to the [[audio-tv|Panasonic TV]]

---

## HP Elitebook 840 G3

| Component | Details |
|---|---|
| Model | HP Elitebook 840 G3 |

### Status

Possibly broken motherboard after inserting an M.2 SATA SSD into the WLAN card slot.

### Diagnosis / Recovery Ideas

- Check if the BIOS/UEFI still posts (external monitor via VGA/DP?)
- The WLAN slot may have shorted power rails — inspect for burned components near the slot
- Try CMOS reset (remove main battery, disconnect CMOS battery, hold power 30s)
- If dead, the SSD and RAM may be salvageable

---

## ASUS Zenbook 14" UHD

| Component | Details |
|---|---|
| Model | ASUS Zenbook UHD 14" |
| Issue | Broken CPU fan |

### Status

Harvested for parts. The M.2 NVMe was removed and installed in the [[desktop-x79|X79 desktop]].
Currently retired unless a replacement fan is sourced.

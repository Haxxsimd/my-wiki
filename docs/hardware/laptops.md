---
tags:
  - hardware
  - laptop
  - linux
  - homelab
---

# Laptops

None of the laptops are set up right now, but all of them still have uses.

## Acer Laptop

| Component | Details |
|---|---|
| Model | Acer (exact model TBD) |
| RAM | 4GB DDR3 |
| Storage | None. Its 128GB SATA SSD is now the boot drive in the [X79 server](desktop-x79.md) |
| OS | None installed |

### History

- Ran Debian 13. Had SSH to the X79 and remote access from the iPhone over Tailscale and Termius. A sudo privilege issue was fixed during setup.
- Hosted Pi-hole until its SSD moved to the X79.

### Possible Roles

With any old SATA drive in it, this is a good low-power always-on box: Pi-hole, Tailscale exit node, or Uptime Kuma.

---

## ASUS Laptop (Headless)

| Component | Details |
|---|---|
| RAM | 4GB DDR3 |
| Display | None. Needs HDMI to an external monitor or TV |
| Storage | None installed. Old laptop HDDs are available |

### Possible Roles

- Secondary homelab node
- Dedicated download box
- Retro gaming station hooked to the [Panasonic TV](audio-tv.md)

---

## HP Elitebook 840 G3

### Status

Possibly a broken motherboard, after an M.2 SATA SSD was inserted into the WLAN card slot.

### Diagnosis / Recovery Ideas

- Check whether the BIOS/UEFI still posts (external monitor over VGA or DP?)
- The WLAN slot may have shorted power rails, so inspect for burned components near the slot
- Try a CMOS reset: remove the main battery, disconnect the CMOS battery, hold power for 30s
- If it is dead, the SSD and RAM can be salvaged

---

## ASUS Zenbook 14" UHD

| Component | Details |
|---|---|
| Issue | Broken CPU fan |

### Status

Harvested for parts. Its M.2 NVMe went to the X79 and has since moved to the [X370 main rig](desktop-x370.md). Retired unless a replacement fan turns up.

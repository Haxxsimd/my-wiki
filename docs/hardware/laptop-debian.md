---
tags:
  - hardware
  - laptop
  - linux
  - debian
  - homelab
---

# Debian 13 Laptop

Newer addition to the setup, running Debian 13.

## Status

- SSH set up between this laptop and the [[desktop-x79|X79 desktop]].
- Resolved a sudo privilege issue on the Debian side during initial setup.
- Reachable remotely via Tailscale + Termius from iPhones.

## Role in the Home Lab

Candidate host (alongside the X79 desktop) for the planned Docker stack:

- Home Assistant
- Frigate NVR
- Pi-hole
- Jellyfin

Final placement — laptop vs. desktop — still TBD. Worth deciding based on power draw (laptop
better for always-on) vs. GPU access (desktop has the GTX 1060, relevant for Frigate's object
detection).

## Specs

| Component | Details |
|---|---|
| Storage | 128GB SATA SSD |
| OS | Debian 13 — plain install, nothing added yet |

*Fill in: model, CPU, RAM.*

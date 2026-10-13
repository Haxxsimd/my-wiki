---
tags:
  - homelab
  - docker
  - plan
---

# Homelab Roadmap

Goal: a small, reliable home server setup that I can explain, rebuild from scratch and show to others. One step at a time, and each step is finished and written down before the next one starts.

## Hardware

- **Server now:** [[desktop-x79|X79]]. Debian 13, 16GB RAM, GTX 1060. Cockpit and Jellyfin already run on it.
- **Server later:** the X370 board with the Ryzen 5 1600X, once the main rig moves to the [[b550-build|B550]]. It idles lower than the Xeon and has AVX2, which the Xeon lacks.
- **Always-on helpers:** the Acer and ASUS laptops, once they have a drive.

## Rules

1. Every service lives in its own folder with a Compose file, and the folder is in git. No secrets in git.
2. If it is not backed up, it does not exist.
3. Every service gets a wiki page: what it does, how it is set up, how to restore it.

## Phase 0: Foundations

- [ ] DHCP reservations in the router for both desktops
- [ ] Consistent hostnames, SSH key login on every machine, then turn off password login
- [ ] Tailscale on every machine
- [ ] tmux on the servers, and Termius or Blink Shell with Mosh on the iPhone instead of iSH
- [ ] `ClientAliveInterval 30` and `ClientAliveCountMax 4` in `sshd_config`
- [ ] Router admin and WiFi passwords changed from the defaults and stored in a password manager

## Phase 1: Docker on the X79

- [ ] Docker Engine and the Compose plugin, installed from Docker's own Debian repository
- [ ] One folder per service under `~/srv/compose/`
- [ ] Jellyfin in Compose, with NVIDIA transcoding (nvidia-container-toolkit)
- [ ] Pi-hole in Compose, with the router handing it out as DNS and a fallback DNS server kept
- [ ] Uptime Kuma
- [ ] Samba share for the iPhone Files app
- [ ] Tailscale subnet router and exit node

## Phase 2: Backups

- [ ] restic or borg from the server to a second drive
- [ ] An offsite copy (a cloud bucket, or a USB drive kept somewhere else)
- [ ] Restore test: delete a service folder and bring it back from backup

## Phase 3: More Services

- [ ] Immich for photos
- [ ] Home Assistant
- [ ] Frigate, once there are cameras
- [ ] Ollama on the GTX 1060

## Phase 4: Proxmox

When the Ryzen server is free, install Proxmox on it and run a Debian VM with Docker inside. Practice snapshots, VM backups and moving a service between nodes.

## Secrets

Passwords and API keys go in a password manager. On the servers they are in `.env` files with `chmod 600`, listed in `.gitignore`. If they ever have to be in git, encrypt them first (sops with age).

## Portfolio Checklist

- [ ] A wiki page per service
- [ ] A separate `homelab` repository with the Compose files and a README
- [ ] A network diagram
- [ ] Screenshots of Cockpit and Uptime Kuma

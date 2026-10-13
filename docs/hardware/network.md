---
tags:
  - network
  - homelab
  - tailscale
---

# Home Network

## Layout

```
Fiber modem ── ASUS ZenWiFi router (192.168.50.0/24)
                 └─ LAN port ── 8-port switch
                                  ├─ X370 main rig   192.168.50.68
                                  ├─ X79 server      192.168.50.190
                                  └─ free ports
```

The router has only two Ethernet ports (one WAN and one LAN), so the 8-port switch on the LAN port gives the wired machines their connections.

## Remote Access

- **Tailscale** connects the iPhone and the desktops, so the same SSH commands work at home and away.
- **SSH from the iPhone** works through iSH (screenshots in the [gallery](gallery.md)), but iSH drops the connection whenever iOS suspends it. Termius or Blink Shell with Mosh, plus tmux on the servers, is the fix.
- **Wake-on-LAN** is set up on the X79.
- **Cockpit** (web console) runs on the X79 at port 9090.
- **Claude Code:** run it on a desktop and drive the session from the iPhone with Remote Control, so nothing needs to be exposed to the internet.

## DNS

Pi-hole is down. It will come back as a container on the [[desktop-x79|X79]].

## To Do

- [ ] DHCP reservations in the router for both desktops
- [ ] Switch the iPhone SSH client from iSH to Termius or Blink
- [ ] Pi-hole back up, with a fallback DNS server in the router
- [ ] Tailscale subnet router and exit node on the X79

## Secrets

API keys and passwords never go into this wiki, because it is public. They live in a password manager. On the machines they are kept in `chmod 600` env files that are never committed.

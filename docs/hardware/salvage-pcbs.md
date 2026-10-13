---
tags:
  - hardware
  - repair
  - salvage
  - soldering
---

# Salvaged Boards & Repairs

## Biltema Speaker System (Art. nr 84-1034, USB2828PR-B)

Found discarded, torn down for parts.

- **Salvaged:** touch-panel interface board, powerbank management board.
- **Plan:** Frankenstein audio project — combine the amp board with salvaged Logitech drivers.
- **Status:** Planning stage.

## 500GB SATA SSD — Connector Repair

- **Drive:** noted earlier as a Crucial M500. The owner remembers it as a Corsair 500GB, so the label needs checking.
- **Problem:** broken SATA connector.
- **Diagnosis:** continuity-tested; short identified and cleared on pin 6 (B+).
- **Plan:** direct-solder repair.
- **Status:** Repair planned, not yet done.

## WD Green 1TB (WD10EZRX) — Repair or Replace

![WD10EZRX label](../assets/devices/wd10ezrx-label.jpg){ width="240" }
![WD10EZRX controller board](../assets/devices/wd10ezrx-pcb.jpg){ width="240" }

- **Drive:** WD10EZRX, 64MB cache, manufactured March 2013.
- **Problem:** bent pins in the SATA power connector. It still shows up in `lsblk` and works, but it can't be trusted.
- **Next steps:**
    1. Read the SMART data (`sudo smartctl -a /dev/sdX`) and look at reallocated sectors, pending sectors and CRC errors.
    2. Try to straighten the pins under magnification with fine tweezers, or keep the drive as scratch storage only.
    3. For anything that matters, such as the media library or backups, replace it. A 13-year-old drive is a liability.
    4. WD Green drives park their heads after 8 seconds idle. If it goes into a server, disable that with `idle3ctl`.
- **Status:** Needs repair or replacement.

## Retired Phones

The broken Android phones and the tablet are out of function and have been retired. See [[phones-tablets]].

---

*Add new salvage/repair entries here as they come up — one subsection per item, with problem,
diagnosis, and status.*

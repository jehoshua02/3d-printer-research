# Bondtech INDX

Automatic tool-changer upgrade kit for the Prusa CORE One. Uses induction heating to power passive "thin tools" wirelessly — no wires on the shuttle.

## Specs

| Field | Value |
|---|---|
| Type | Upgrade kit (not standalone printer) |
| Base printer | Prusa CORE One |
| Tools | Up to 8 |
| Tool change time | 8–12 sec (heat-up as fast as 4 sec) |
| Purge waste | Near-zero — each tool has its own nozzle, no cross-contamination |
| Build volume | CORE One's volume (~250×210×220 mm), slightly reduced by tool rack |
| Speed | Inherits CORE One's CoreXY speed |
| Price | Smart toolhead ~350 EUR + ~35 EUR per passive tool; full 8-tool kit ~630 EUR |
| Firmware | Klipper, Kalico, RRF |
| Availability | Pre-orders sold out; retail Q2 2026 via Prusa shop |

## vs Prusa XL

Prusa XL has active toolheads (full hotend per head, up to 5 tools, ~$4,500+ fully loaded, 360×360×360 mm build volume). INDX is cheaper, more tools, zero purge, but smaller volume and longer swap time.

## Community reception

Founder's Edition sold out in ~1 hour. Generally positive; concerns about swap speed (8–12 sec vs XL's ~4 sec adds up over 1,000 swaps).

## Open source toolchanger competitors

### TapChanger
Voron 2 mod. Nozzle-probe + toolchanger, up to 6 hotends in 350 frame, no servos, no wires on shuttle. Pure DIY/free.
- [GitHub](https://github.com/viesturz/tapchanger)

### StealthChanger
Voron 2.4 tool-changing system by DraftShift. Supports many toolheads (Stealthburner, Dragon Burner, XOL, etc.). Available as LDO kit for easier assembly.
- [Website](https://stealthchanger.com/)
- [GitHub](https://github.com/DraftShift/StealthChanger)

### E3D ToolChanger
Pioneer of open-source toolchanging. Now discontinued but files remain open source.
- [GitHub](https://github.com/e3donline/ToolChanger)

## Sources

- [Tom's Hardware — Tool Changer Wars](https://www.tomshardware.com/3d-printing/3d-printings-tool-changer-wars-heat-up-as-prusa-re-enters-the-ring)
- [Prusa blog — XL in 2026](https://blog.prusa3d.com/xl-in-2026-new-toolheads-lower-price_129707/)
- [Prusa forum discussion](https://forum.prusa3d.com/forum/prusa-core-one-l-general-discussion-announcements-and-releases/bondtech-indx-on-coreonel/)
- [Voron forum discussion](https://forum.vorondesign.com/threads/bondtech-indx.2322/)
- [All3DP coverage](https://all3dp.com/4/new-bondtech-indx-toolchanger-release-details-revealed/)
- [Klipper community thread — which toolchanger?](https://klipper.discourse.group/t/ive-been-reading-about-toolchangers-which-one-should-i-get/15886)

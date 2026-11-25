# M490D · Input Pre Amps

Ward-Beck Systems M490D, 1978|11. Wiki page: [M490D on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M490D.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 8 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 5 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 13 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 2 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 7 |

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa3NjazFGbFctaFk/view?resourcekey=0-TdIIeGfZJM5bGp8Kuh_NUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa3NjazFGbFctaFk&resourcekey=0-TdIIeGfZJM5bGp8Kuh_NUw" width="240" alt="1978 - M490D - 490-04-012 - LINE INPUT MODULE FRONT PANEL.jpg"></a><br><sub>1978|11 · 490-04-012 - LINE INPUT MODULE FRONT PANEL · <a href="MECHANICAL/1978%20-%20M490D%20-%20490-04-012%20-%20LINE%20INPUT%20MODULE%20FRONT%20PANEL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbzF2SklSVmlCLTQ/view?resourcekey=0-Dz23WkI9IBj1kz7h8dWdQQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbzF2SklSVmlCLTQ&resourcekey=0-Dz23WkI9IBj1kz7h8dWdQQ" width="240" alt="1978 - M490D - schem-490-02-005 (2).pdf"></a><br><sub>1978|11 · schem-490-02-005 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUDhFS0FrbFMxQlE/view?resourcekey=0-AKtokXE-8Tkj3dBq5LA2Cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUDhFS0FrbFMxQlE&resourcekey=0-AKtokXE-8Tkj3dBq5LA2Cw" width="240" alt="1978 - M490D - schem-490-02-005.pdf"></a><br><sub>1978|11 · schem-490-02-005</sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdFJKOHMteDZGOTA/view?resourcekey=0-sWzd1lKE_HUh1cCSLqQCLA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdFJKOHMteDZGOTA&resourcekey=0-sWzd1lKE_HUh1cCSLqQCLA" width="240" alt="1978 - M490D - pinout-490-04-005 (2).pdf"></a><br><sub>1978|11 · pinout-490-04-005 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUDZxUGUxeDNHZmc/view?resourcekey=0-vavplF7UU2j9R3IentnScQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUDZxUGUxeDNHZmc&resourcekey=0-vavplF7UU2j9R3IentnScQ" width="240" alt="1978 - M490D - pinout-490-04-005.pdf"></a><br><sub>1978|11 · pinout-490-04-005</sub></td></tr>
</table>

Not on Google Drive yet: `M490D - RTO-144 Connections.pdf`

## RTO-144 pinout

25 contacts, 4 contacts (P1), 21 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | PGM 1 OUT, LEFT | out |  | high |
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | PGM 1 OUT, LEFT | out |  | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 3 | PGM 1 OUT, RIGHT | out |  | high |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | PGM 1 OUT, RIGHT | out |  | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 5 | PGM 2 OUT, LEFT | out |  | high |
| 6 | PGM 2 OUT, LEFT | out |  | high |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | PGM 2 OUT, RIGHT | out |  | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 8 | PGM 2 OUT, RIGHT | out |  | high |
| 9 | SHIELO | other |  | high |
| 10 | NC | nc |  | high |
| 11 | AUX OUT, LEFT | out |  | high |
| 12 | AUX OUT, LEFT | out |  | high |
| 12 |  | unread |  | low |
| 13 | AUX OUT, RIGHT | out |  | high |
| 14 | AUX OUT, RIGHT | out |  | high |
| 15 | CUE OUT, LEFT | out |  | high |
| 15 |  | unread |  | low |
| 16 | CUE OUT, LEFT | out |  | high |
| 17 | CUE OUT, RIGHT | out |  | high |
| 17 |  | unread |  | low |
| 18 | CUE OUT, RIGHT | out |  | high |
| 19 | NC | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | NC | nc |  | high |
| 20 | COMMON | ground |  | high |
| 21 | NC | nc |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| 25 | V COM | ground |  | high |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |
| L |  | unread |  | low |
| N |  | unread |  | low |
| R |  | unread |  | low |
| U |  | unread |  | low |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWpQQmVFQ2sxUkk/view?resourcekey=0-mNScEkcSWrf50rW-3Qb5PA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWpQQmVFQ2sxUkk&resourcekey=0-mNScEkcSWrf50rW-3Qb5PA" width="240" alt="1978 - M490D - 002.jpg"></a><br><sub>1978|11 · 002</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1978|11 · 001](https://drive.google.com/file/d/0B0yR0b5T78SKX0kxdGtMeWtSTVk/view?resourcekey=0-RtHv7DAPs-06cvDnKDFBAA)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M490D - schem-490-02-005 p1.kicad_sch](KICAD/1978%20-%20M490D%20-%20schem-490-02-005%20p1.kicad_sch)
- [M490D.kicad_sym](KICAD/M490D.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

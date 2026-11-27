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

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [8 topics](FORUM.md): what owners and technicians said about it.

<!-- /module data -->

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

Read from 2 pinout pictures (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 15 of 15 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- insert guessed: Which of the eight INSERT contacts (P2-E,F,H,J,5,6,7,8) are send vs return, and their polarity / channel, is not shown. (M490D: 1978 - M490D - pinout-490-04-005 (2).pdf)
- insert guessed: Which of the eight INSERT contacts (P2-E,F,H,J,5,6,7,8) are send vs return, and their polarity / channel, is not shown. (M490D: 1978 - M490D - pinout-490-04-005.pdf)

**Inserts:** INSERT: INSERT SEND → INSERT RETURN

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-1 | PGM 1 OUT LEFT | out | PGM 1 OUT LEFT | medium |
| P1-2 | PGM 1 OUT LEFT | out | PGM 1 OUT LEFT | medium |
| P1-3 | PGM 1 OUT RIGHT | out | PGM 1 OUT RIGHT | medium |
| P1-4 | PGM 1 OUT RIGHT | out | PGM 1 OUT RIGHT | medium |
| P1-5 | PGM 2 OUT LEFT | out | PGM 2 OUT LEFT | medium |
| P1-6 | PGM 2 OUT LEFT | out | PGM 2 OUT LEFT | medium |
| P1-7 | PGM 2 OUT RIGHT | out | PGM 2 OUT RIGHT | medium |
| P1-8 | PGM 2 OUT RIGHT | out | PGM 2 OUT RIGHT | medium |
| P1-9 | OUTPUT SHIELD | shield | shield | medium |
| P1-10 | N/C | nc |  | medium |
| P1-11 | AUX OUT LEFT | out | AUX OUT LEFT | medium |
| P1-12 | AUX OUT LEFT | out | AUX OUT LEFT | medium |
| P1-13 | AUX OUT RIGHT | out | AUX OUT RIGHT | medium |
| P1-14 | AUX OUT RIGHT | out | AUX OUT RIGHT | medium |
| P1-15 | CUE OUT LEFT | out | CUE OUT LEFT | medium |
| P1-16 | CUE OUT LEFT | out | CUE OUT LEFT | medium |
| P1-17 | CUE OUT RIGHT | out | CUE OUT RIGHT | medium |
| P1-18 | CUE OUT RIGHT | out | CUE OUT RIGHT | medium |
| P1-19 | N/C | nc |  | medium |
| P1-20 | N/C | nc |  | medium |
| P1-21 | N/C | nc |  | medium |
| P1-22 | CHASSIS | ground |  | medium |
| P2-1 | LINE B IN | in | LINE B IN | medium |
| P2-2 | N/C | nc |  | medium |
| P2-3 | LINE A IN | in | LINE A IN | medium |
| P2-4 | N/C | nc |  | medium |
| P2-5 | INSERT | other |  | medium |
| P2-6 | INSERT | other |  | medium |
| P2-7 | INSERT | other |  | medium |
| P2-8 | INSERT | other |  | medium |
| P2-9 | SHIELD | shield | shield | medium |
| P2-10 | LINE A CTL | control_in | LINE A CTL | medium |
| P2-11 | EXT CUE | control_in | EXT CUE | medium |
| P2-12 | EXT CH OFF | control_in | EXT CH OFF | medium |
| P2-13 | CH A CTL OUT | control_out | CH A CTL OUT | medium |
| P2-14 | N/C | nc |  | medium |
| P2-15 | ON CTL | control_in | ON CTL | medium |
| P2-16 | IC (INTERNALLY CONNECTED) | other |  | medium |
| P2-17 | OFF CTL | control_in | OFF CTL | medium |
| P2-18 | OFF TALLY | control_out | OFF TALLY | medium |
| P2-19 | -25 V | power |  | medium |
| P2-20 | 25V COM | ground |  | medium |
| P2-21 | +25 V | power |  | medium |
| P2-22 | CTL COM | ground |  | medium |
| P2-A | LINE B IN | in | LINE B IN | medium |
| P2-B | N/C | nc |  | medium |
| P2-C | LINE A IN | in | LINE A IN | medium |
| P2-D | N/C | nc |  | medium |
| P2-E | INSERT | other |  | medium |
| P2-F | INSERT | other |  | medium |
| P2-H | INSERT | other |  | medium |
| P2-J | INSERT | other |  | medium |
| P2-K | SHIELD | shield | shield | medium |
| P2-L | LINE B CTL | control_in | LINE B CTL | medium |
| P2-M | LINE CTL COM | ground |  | medium |
| P2-N | EXT CH ON | control_in | EXT CH ON | medium |
| P2-P | CH B CTL OUT | control_out | CH B CTL OUT | medium |
| P2-R | TIMER RESET | control_out | TIMER RESET | medium |
| P2-S | ON CTL | control_in | ON CTL | medium |
| P2-T | IC (INTERNALLY CONNECTED) | other |  | medium |
| P2-U | OFF CTL | control_in | OFF CTL | medium |
| P2-V | OFF TALLY | control_out | OFF TALLY | medium |
| P2-W | -25 V | power |  | medium |
| P2-X | 25V COM | ground |  | medium |
| P2-Y | +25 V | power |  | medium |
| P2-Z | CTL COM | ground |  | medium |

**Straps:** JMP.6.7: P2-6 P2-7 · JMP.F.H: P2-F P2-H

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

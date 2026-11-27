# M415 · Dynamics

Ward-Beck Systems M415, 1971|4. Wiki page: [M415 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M415.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 64 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 19 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 18 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 7 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 32 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1971 - M415 - p5.jpg](MANUALS/1971%20-%20M415%20-%20p5.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Attack time** | Less than 100 microseconds |
| **Recovery time** | second, seconds, seconds |
| **Phasing** | LoW terminal number of input in phase with low terminal number of output. |
| **Mute** | Internal mute relay controlled by closure to ground energize to unmute |
| **Power requirements** | 1l5v AC 6VA |
| **Ambient temperature** | 00 to 508c |
| **Dimensions** | 2 &quot;H X 7 &quot;W X 16&quot;L |
| **Weight** | 5lbs |
| **Optional noise reduction** |  |
| &nbsp;&nbsp;Expansion ratio | 2:1 |
| **Expansion range** | 10 dB |
| **Expansion threshold** | Factory set 10 to 20 dB below compression threshold |
| **Attack time** | Less than 50 microseconds |
| **Release time** | 100 milli seconds |

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLW9pSGhvNDl0Z1k/view?resourcekey=0-R6Ikhe1XRxYgO-8Ef30WQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLW9pSGhvNDl0Z1k&resourcekey=0-R6Ikhe1XRxYgO-8Ef30WQw" width="240" alt="1971 - M415 - WBS 415 inside a.jpg"></a><br><sub>1971|4 · WBS 415 inside a</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWEUtdkZUaXc4VkE/view?resourcekey=0-TAltBPadw0AzomdTq1BAlg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWEUtdkZUaXc4VkE&resourcekey=0-TAltBPadw0AzomdTq1BAlg" width="240" alt="1971 - M415 - WBS 415 inside b.jpg"></a><br><sub>1971|4 · WBS 415 inside b</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1ObPdE6lTMpsj6iZvEL6cMV5pHmZBM835/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1ObPdE6lTMpsj6iZvEL6cMV5pHmZBM835" width="240" alt="1971 - M415 - DOC - 415-03-006 - REMOVE ALL BURRS SHARP EDGES.jpg"></a><br><sub>1971|4 · DOC - 415-03-006 - REMOVE ALL BURRS SHARP EDGES</sub></td></tr>
</table>

Not on Google Drive yet: `1971 - 415-03-002 - SUB CHASSIS DETAIL - DRN DPS - ISS 3 (2).jpg`, `1971 - 415-03-002 - SUB CHASSIS DETAIL - DRN DPS - ISS 3.jpg`, `1971 - 415-03-005 - CONNECTOR MTG. BKT - DRN DPS - ISS 2.jpg`, `1971 - 415-03-006 - MOUNTING BAR - ISS 1.jpg`

## 3-D model

[`MECHANICAL/M415.stl`](MECHANICAL/M415.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M415)

- **Size:** 177.8 × 50.8 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 2 "H X 7 "W X 16"L)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M415 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M415.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/17fjMF5NzBueHHDcFkhGsmlm0sS_X2ThA/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=17fjMF5NzBueHHDcFkhGsmlm0sS_X2ThA" width="240" alt="1971 - 415-02-002 - COMPRESSOR CONTROL SYSTEM SCHEMATIC - DRN DPS - ISS 3 (2).jpg"></a><br><sub>1971|4 · 415-02-002 - COMPRESSOR CONTROL SYSTEM SCHEMATIC - DRN DPS - ISS 3 (2) · <a href="SCHEMATICS/1971%20-%20415-02-002%20-%20COMPRESSOR%20CONTROL%20SYSTEM%20SCHEMATIC%20-%20DRN%20DPS%20-%20ISS%203%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1dU3u7hofm6Ox90hHQv7uvuKEILDHdKtf/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1dU3u7hofm6Ox90hHQv7uvuKEILDHdKtf" width="240" alt="1971 - 415-02-002 - COMPRESSOR CONTROL SYSTEM SCHEMATIC - DRN DPS - ISS 3.jpg"></a><br><sub>1971|4 · 415-02-002 - COMPRESSOR CONTROL SYSTEM SCHEMATIC - DRN DPS - ISS 3 · <a href="SCHEMATICS/1971%20-%20415-02-002%20-%20COMPRESSOR%20CONTROL%20SYSTEM%20SCHEMATIC%20-%20DRN%20DPS%20-%20ISS%203%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2lQSTI5VGVHZ00/view?resourcekey=0-jaGNs5bpvOXbA6AFRcelTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2lQSTI5VGVHZ00&resourcekey=0-jaGNs5bpvOXbA6AFRcelTQ" width="240" alt="1971 - M415 - 415-02-002 - MUSEEDECRAE BIGE SVEHEONGLES.jpg"></a><br><sub>1971|4 · 415-02-002 - MUSEEDECRAE BIGE SVEHEONGLES · <a href="SCHEMATICS/1971%20-%20M415%20-%20415-02-002%20-%20MUSEEDECRAE%20BIGE%20SVEHEONGLES%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMjJxRHNKdE56Vnc/view?resourcekey=0-yVV0sDIzaHBX0-52dmdr6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMjJxRHNKdE56Vnc&resourcekey=0-yVV0sDIzaHBX0-52dmdr6Q" width="240" alt="1971 - M415 - 415-02-003 - SYSTETS LID CSOL.jpg"></a><br><sub>1971|4 · 415-02-003 - SYSTETS LID CSOL · <a href="SCHEMATICS/1971%20-%20M415%20-%20415-02-003%20-%20SYSTETS%20LID%20CSOL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZTU5cFVGLTl4SVE/view?resourcekey=0-6slyPY-OQHSQ54ht7j_cpQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZTU5cFVGLTl4SVE&resourcekey=0-6slyPY-OQHSQ54ht7j_cpQ" width="240" alt="1971 - M415 - 416-06-001 - MNSBEREGEABHES SEHE ANGLES.jpg"></a><br><sub>1971|4 · 416-06-001 - MNSBEREGEABHES SEHE ANGLES · <a href="SCHEMATICS/1971%20-%20M415%20-%20416-06-001%20-%20MNSBEREGEABHES%20SEHE%20ANGLES%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1m8pDrBqNnohbKQByQ9_Kq1OmKQjM1IkU/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1m8pDrBqNnohbKQByQ9_Kq1OmKQjM1IkU" width="240" alt="19xx - 415-02-001 - COMPRESSOR AMPLIFIER SCHEMATIC - ISS 4.jpg"></a><br><sub>19xx - 415-02-001 - COMPRESSOR AMPLIFIER SCHEMATIC - ISS 4 · <a href="SCHEMATICS/19xx%20-%20415-02-001%20-%20COMPRESSOR%20AMPLIFIER%20SCHEMATIC%20-%20ISS%204%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1971|4 · M415 - 8415-02-001 - MICROPHONE INPUT 88 DB MAX. (TRANSDUCER) - COMPONENT LAYOUT](https://drive.google.com/file/d/0B0yR0b5T78SKTVFjeVVMRFp4Vzg/view?resourcekey=0-GGKX_rSsPSDutVse6fgaKg)

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0tmWWwzeTJJRlk/view?resourcekey=0-HDSRKmBgvpkAVeSe9BXJSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0tmWWwzeTJJRlk&resourcekey=0-HDSRKmBgvpkAVeSe9BXJSw" width="240" alt="1971 - M415 - MANUAL INDEX M415 COMPRESSOR AMPLIFIER.jpg"></a><br><sub>1971|4 · MANUAL INDEX M415 COMPRESSOR AMPLIFIER</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSm5UM1l3NGhaQXc/view?resourcekey=0-xcsdx8mz9JNRE_WUk7qzYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSm5UM1l3NGhaQXc&resourcekey=0-xcsdx8mz9JNRE_WUk7qzYQ" width="240" alt="1971 - M415 - p1.jpg"></a><br><sub>1971|4 · p1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFRTTVd4eXVlU28/view?resourcekey=0-6dYrlApDow86WvHJ5Mg4WQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFRTTVd4eXVlU28&resourcekey=0-6dYrlApDow86WvHJ5Mg4WQ" width="240" alt="1971 - M415 - p10.jpg"></a><br><sub>1971|4 · p10</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVM0Vmg1ZC1aZVU/view?resourcekey=0-A2LUXnjS1InWzgWUEf49hA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVM0Vmg1ZC1aZVU&resourcekey=0-A2LUXnjS1InWzgWUEf49hA" width="240" alt="1971 - M415 - p11.jpg"></a><br><sub>1971|4 · p11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDJjN2lRYTRXcnM/view?resourcekey=0-qo--9E__CHgKkj97111pVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDJjN2lRYTRXcnM&resourcekey=0-qo--9E__CHgKkj97111pVw" width="240" alt="1971 - M415 - p12.jpg"></a><br><sub>1971|4 · p12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYy1GdVVOZ1RmakE/view?resourcekey=0-ys54uuzbFBH18E6uPyM4Rw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYy1GdVVOZ1RmakE&resourcekey=0-ys54uuzbFBH18E6uPyM4Rw" width="240" alt="1971 - M415 - p13.jpg"></a><br><sub>1971|4 · p13</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaTJGVjdpS1paOVU/view?resourcekey=0-PJTKV-Th6N86Zj-OKS9EAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaTJGVjdpS1paOVU&resourcekey=0-PJTKV-Th6N86Zj-OKS9EAw" width="240" alt="1971 - M415 - p14.jpg"></a><br><sub>1971|4 · p14</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzZEZXlfMnRLVUE/view?resourcekey=0-QXIYecFVE-VMKgTatmq9DA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzZEZXlfMnRLVUE&resourcekey=0-QXIYecFVE-VMKgTatmq9DA" width="240" alt="1971 - M415 - p2.jpg"></a><br><sub>1971|4 · p2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUW8yakNuX0UwMTg/view?resourcekey=0-z65K2O_U_YkuMchiqYF-ng" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUW8yakNuX0UwMTg&resourcekey=0-z65K2O_U_YkuMchiqYF-ng" width="240" alt="1971 - M415 - p4.jpg"></a><br><sub>1971|4 · p4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT24ydUQxb1FmNkU/view?resourcekey=0--WEgFm8YlTWo6z3EmqZoAQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT24ydUQxb1FmNkU&resourcekey=0--WEgFm8YlTWo6z3EmqZoAQ" width="240" alt="1971 - M415 - p5.jpg"></a><br><sub>1971|4 · p5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKakhST0lRUC1rUU0/view?resourcekey=0-gApW5D1Yx7KeK-ZNSpZl2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKakhST0lRUC1rUU0&resourcekey=0-gApW5D1Yx7KeK-ZNSpZl2w" width="240" alt="1971 - M415 - p6.jpg"></a><br><sub>1971|4 · p6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNml2NkJYZlRqaFk/view?resourcekey=0-VhVHUtwmd9UCR7Ch1z4MKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNml2NkJYZlRqaFk&resourcekey=0-VhVHUtwmd9UCR7Ch1z4MKw" width="240" alt="1971 - M415 - p7.jpg"></a><br><sub>1971|4 · p7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYl9mWEdXRGZORFk/view?resourcekey=0-581OwdII7uOvTR2WnPNxNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYl9mWEdXRGZORFk&resourcekey=0-581OwdII7uOvTR2WnPNxNQ" width="240" alt="1971 - M415 - p8.jpg"></a><br><sub>1971|4 · p8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNmhVcGJ5SThTOHc/view?resourcekey=0-lspGpleyB8Q0jRR9dVOA5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNmhVcGJ5SThTOHc&resourcekey=0-lspGpleyB8Q0jRR9dVOA5w" width="240" alt="1971 - M415 - p9.jpg"></a><br><sub>1971|4 · p9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M415 - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1WR7q2-mPGhOc6rDi0U7UMazdnIyeSDpM/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1WR7q2-mPGhOc6rDi0U7UMazdnIyeSDpM" width="240" alt="19xx - M415 - DOC - Scan_20210323 (2).jpg"></a><br><sub>19xx - M415 - DOC - Scan_20210323 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1fS-aGGfxQq_3RK23Wb-vBQZkHHXOfYNZ/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1fS-aGGfxQq_3RK23Wb-vBQZkHHXOfYNZ" width="240" alt="19xx - M415 - DOC - Scan_20210323.jpg"></a><br><sub>19xx - M415 - DOC - Scan_20210323</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1971 - 415-02-002 - COMPRESSOR CONTROL SYSTEM SCHEMATIC - DRN DPS - ISS 3 (2).kicad_sch](KICAD/1971%20-%20415-02-002%20-%20COMPRESSOR%20CONTROL%20SYSTEM%20SCHEMATIC%20-%20DRN%20DPS%20-%20ISS%203%20(2).kicad_sch)
- [1971 - 415-02-002 - COMPRESSOR CONTROL SYSTEM SCHEMATIC - DRN DPS - ISS 3.kicad_sch](KICAD/1971%20-%20415-02-002%20-%20COMPRESSOR%20CONTROL%20SYSTEM%20SCHEMATIC%20-%20DRN%20DPS%20-%20ISS%203.kicad_sch)
- [1971 - M415 - 415-02-002 - MUSEEDECRAE BIGE SVEHEONGLES.kicad_sch](KICAD/1971%20-%20M415%20-%20415-02-002%20-%20MUSEEDECRAE%20BIGE%20SVEHEONGLES.kicad_sch)
- [1971 - M415 - 415-02-003 - SYSTETS LID CSOL.kicad_sch](KICAD/1971%20-%20M415%20-%20415-02-003%20-%20SYSTETS%20LID%20CSOL.kicad_sch)
- [1971 - M415 - M415 - 8415-02-001 - MICROPHONE INPUT 88 DB MAX. (TRANSDUCER) - COMPONENT LAYOUT p5.kicad_sch](KICAD/1971%20-%20M415%20-%20M415%20-%208415-02-001%20-%20MICROPHONE%20INPUT%2088%20DB%20MAX.%20(TRANSDUCER)%20-%20COMPONENT%20LAYOUT%20p5.kicad_sch)
- [19xx - 415-02-001 - COMPRESSOR AMPLIFIER SCHEMATIC - ISS 4.kicad_sch](KICAD/19xx%20-%20415-02-001%20-%20COMPRESSOR%20AMPLIFIER%20SCHEMATIC%20-%20ISS%204.kicad_sch)
- [M415.kicad_sym](KICAD/M415.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

# Retro Computer Cheatsheets

One-page, print-ready quick-reference sheets for the BASIC dialects and system commands of classic 8-bit home computers. Each sheet is a densely packed, color-coded "cram sheet" designed to sit next to the machine (or the emulator) — the kind of thing you keep within arm's reach while typing in a program listing.

Every sheet fits on a **single US Letter page** and is built to print at **100% scale**.

---

## What's on each sheet

### [Apple \]\[ cheatsheet](Apple_II_Cheatsheet.pdf)

Applesoft BASIC (program control, statements, operators, the full function list, text/cursor commands, lo-res and hi-res graphics), DOS 3.3 and ProDOS / BASIC.SYSTEM command sets, the machine monitor (`CALL -151`) syntax, the I/O soft switches at `$C000–$C057`, handy `CALL` routines, the 64K memory map, the lo-res 16-color and hi-res 8-color palettes, key `CHR$` codes, and the escape-mode editing keys. Targets the II, II+, IIe and IIc. 

### [Commodore cheatsheet](Commodore_Cheatsheet.pdf)
Core Commodore BASIC shared across the family, with extras tagged by version — **1.0–4.0** (PET/CBM), **2.0** (VIC-20, C64), **3.5** (C16, Plus/4), and **7.0** (C128). Includes disk & tape I/O with the `,8` device syntax, the disk DOS commands sent over channel 15 (`N0:`, `S0:`, `R0:`…), PETSCII screen and color control codes, and C64-specific memory / SID sound / sprite POKE tables, plus a per-machine quick-facts strip (screen RAM, color RAM, reset `SYS`). A dedicated panel covers the **Commodore 64 Ultimate** (2025) menu and hotkeys — `C= + RESTORE` to open the Ultimate menu, joystick-port swap, NTSC/PAL boot select, and reset/shutdown.

### [TI-99/4A cheatsheet](TI-99-4A_Cheatsheet.pdf)
TI BASIC and TI Extended BASIC side by side, with `[XB]` marking the cartridge-only features. The `CALL` subprograms get their own cards (graphics, sprites & motion, sound & input), alongside the 16-color set, the device/file system (`DSK1.`, `CS1`, `PIO`, `RS232`), and the FCTN gold-key map — including the warning that `FCTN+=` (QUIT) erases your program.

### [Coleco ADAM cheatsheet](Coleco_ADAM_Cheatsheet.pdf)
Built around the fact that **SmartBASIC is an Applesoft ][ work-alike**, so the BASIC cards mirror the Apple sheet and the focus falls on the ADAM-specific parts: the D1/D2 Digital Data Pack drives, the D5/D6 disk drives, `LOAD`/`SAVE`/`CATALOG` with a `,Dn` drive specifier, `FORMAT`, EOS and OS-7 booting, and the hardware differences (TMS9928A video, Z80A CPU, daisy-wheel printer).

### [Atari 400/800 cheatsheet](Atari_400-800_Cheatsheet.pdf)
Atari BASIC with its quirks called out up front — substrings via `A$(start,end)` (there is **no** `LEFT$`/`MID$`/`RIGHT$`), and **no** `DEF FN`. Covers the graphics modes table, the `SETCOLOR` registers, POKEY sound, the essential PEEK/POKE locations (752 cursor, 710/712 colors, 53279 console keys, …), CIO device names, the DOS 2.x menu, and the editing & special keys.

---

## Printing

- Print at **100% / actual size** (turn off "fit to page" / "shrink to fit").
- Paper size is **US Letter** (8.5 × 11 in). For A4, choose "fit to printable area" — the layout will scale down slightly but stays readable.
- The type runs roughly 7 pt to keep everything on one page; a laser printer or a decent inkjet at 600 dpi gives the crispest result.

---

## Accuracy & corrections

These sheets aim to be accurate to the original hardware and ROM/BASIC versions, but the 8-bit world is full of model-to-model variations, revisions, and edge cases. If you spot an error or something that differs on your particular machine or ROM revision, please **open an issue** or send a **pull request** — corrections from the community are very welcome.

---

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

*All product names, trademarks, and BASIC dialects belong to their respective owners. These reference sheets are an independent, educational compilation for the retro-computing community.*

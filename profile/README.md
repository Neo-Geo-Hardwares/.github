# Neo-Geo Hardwares repository

Neo-Geo was introduced to the world on 1990.

The Neo Geo originally launched as the Multi Video System (MVS) coin-operated arcade machine.

With its games stored on self-contained cartridges, a game cabinet can easily be changed to a different game title by swapping the game's cartridge and cabinet artwork.

The Neo Geo was marketed as the first 24-bit system; its CPU is actually a 16/32-bit 68000 with an 8-bit Z80 coprocessor, while its GPU chipset has a 24-bit graphics data bus.
It was design as two separate (but compatible) market branches MVS and AES.

## Why this project

Until now, only poorly scanned schematics documentation is available and for only one AES model and one MVS, despite an huge communities, no good scan or documents exist.
Their is a lot of usefull resources, but so far I never seen any "modern" or good scan schematics.

This project is trying to re-create schemactics for the Neo-Geo from the existing copy.

## About the author

Some words about me, Frater, I'm working on this project as an hobbyiest, trying to fix some of my MVS board.

## Methodology

I do use an edited photo with the underlayer PCB "visible" over the top layer.

![under and upper layers](https://github.com/Neo-Geo-Hardwares/.github/blob/main/img/Board-2layers.png)

## MVS

The Neo Geo originally launched as the Multi Video System (MVS) coin-operated arcade machine. With its games stored on self-contained cartridges, a game cabinet can easily be changed to a different game title by swapping the game's cartridge and cabinet artwork.

serverals hardware revision exist:
 * MV1(T)
 * MV1A
 * MV1ACH
 * MV1AX
 * MV1B
 * MV1B1
 * MV1C
 * [MV1F(S)](https://github.com/Neo-Geo-Hardwares/Schematics-MV1F)
 * MV1FZ(S)
 * MV2B
 * MV2F
 * MV2FS
 * MV4
 * MV4F(S)
 * MV4FT
 * MV6

## Usefull sources used for thoses repos.


## Specifications

The system uses seven different specialist processors, which divide the workload for the visuals, audio and gameplay.

### CPU
Main CPU processor: Motorola 68000 (often a second sourced version, usually by Toshiba or Hitachi, initially a Hitachi HD68HC000PS12) @ 12 MHz (16/32-bit instructions)
CPU co-processor: Zilog Z80 @ 4 MHz (also used as audio controller) (8/16-bit instructions)

### Memory
RAM: 214 KB SRAM
 * Main 68000 RAM: 64 KB (32 KB SRAM ×2)
 * Video RAM: 84 KB SRAM
   * Main VRAM: 64 KB (32 KB SRAM ×2)
   * Palette memory: 16 KB (8 KB SRAM ×2)
   * Fast video sprite RAM: 4 KB (2 KB SRAM ×2)
* Z80 sound RAM: 2 KB SRAM
* Battery-backup save NVRAM: 64 KB SRAM (MVS only)

On-board ROM: 512 KB
 * Zoom look-up table: 128 KB
 * Fix layer graphics: 128 KB
 * Z80 sound: 128 KB
 * 68000 BIOS: 128 KB

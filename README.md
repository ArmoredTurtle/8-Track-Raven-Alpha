8-Track Raven 4 spool automated filament changer.

V0.0.41

Join our discord server here:

[![Join me on Discord](https://discord.com/api/guilds/1229586267671629945/widget.png?style=banner2)](https://discord.gg/eT8zc3bvPR)


## Intro

This is an alpha version of the 8-Track project.
8-Track is a modular automated filament changer that is scaleable and compatible with any KLIPPER 3d printer.
Specifically 8-Track Raven's purpose is to do public testing of critical components at a lower price point.
Raven retains the same cassettes as the 8-Track while simplifying the hub and uses an off the shelf MCU.

## Objectives
The goal of alpha testing this project is to refine the cassettes as much as possible and prove reliability of the system.
Features like active filament drying are being worked on but do not currently have a timeline.

## Compatibility
Almost everything is subject to change unless specified as set in stone such as:
Cassette dimensions, 8-Track Raven frame.

# Raven BOM (Bill of Materials)

## Frame
| Qty | Item                  |
|-----|-----------------------|
| 4   | 412.5 2020 extrusions |
| 2   | 304.5 2020 extrusions |
| 2   | 219mm extrusions      |
| 8   | M5x25 BHCS            |
| 2   | M5x8 BHCS             |
| 2   | M5 Roll Nuts          |

## Hardware
| Qty | Item                          |
|-----|-------------------------------|
| 4   | B-side cassete PCBs           |
| 56  | M3x5 Heat set inserts         |
| 16  | 0.5x5x15 Coil Springs         |
| 16  | M3x20 FHCS                    |
| 32  | M3x12 SHCS                    |
| 32  | M5 Roll nuts                  |
| 32  | M5x10 BHCS                    |
| 11  | ECAS04 (remove rubber spacer) |

## Printed Parts
| Qty    | Part Name                     |
|--------|-------------------------------|
| 1 - 4  | Backer_X                      |
|   4    | Backer_PCB_Spring_Plate_x4    |
| 1-4    | Drop_Plate_X                  |
| 1      | Mid_Plate_Lower               |
| 1      | Mid_Plate_Upper               |
| 1      | 6-1_Hub                       |
| 1      | BTT_MMB_CAN_Mount             |

# Cassette BOM ((Bill of Materials)  Per Cassette)

## Electronics
| Qty | Item                            |
|-----|---------------------------------|
| 1   | 20mm Nema 17 motor              |
| 1   | Endstop microswitch (Omron D2F) |
| 1   | mg 996r servo                   |
| 1   | Cassette Side-A PCB             |

## Hardware
|  Qty  | Item                                                                                           |
|-------|------------------------------------------------------------------------------------------------|
|  21   | M3x6 SHCS                                                                                      |
|  6    | M3x8 SHCS                                                                                      |
|  7    | M3x20 SHCS                                                                                     |
|  3    | M3x20 FHCS                                                                                     |
|  6    | M3 Washer                                                                                      |
|  20   | M3x5 Heat set inserts                                                                          |
|  1    | BMG Extruder gear kit                                                                          |
|  1    | Spring (6mm OD, 1mm Wire Size, 7.5mm Compressed Length, 15mm Free Length, 37.2N Load Capacity) |
|  2    | #211 Orings (13/16" ID, 1 1/16" OD)                                                            |
|  4    | 608 Bearings                                                                                   |
|  1    | R4zz Bearing OR 634ZZ (print tension arms)                                                     |
|  2    | 80x8mm Shaft                                                                                   |
|  1    | HF081412 one way bearing (8mm ID, 14mm OD, 12mm L)                                             |
|  1    | 5mm Steel ball bearing                                                                         |
| ~32mm | 4mm OD 3mm ID bowden tube                                                                      |
|  4    | 6x3mm magnets                                                                                  |
|  1    | 0.5x5x15 Coil Spring                                                                           |
| ***   | If split cassette +1 M3x6 SHCS, +1 M3X5 heat set insert                                        |

## Printed Parts
| Qty | Item                  |
|-----|-----------------------|
| 1   | Cassette Lid          |
| 1   | Cassette Shell        |
| 1   | Frane                 |
| 1   | Idler Frame           |
| 1   | TensionArm_Upper      |
| 1   | TensionArm_Lower      |
| 2   | Idler Roller          |
| 2   | Idler Spacer          |
| 2   | Inner Roller          |
| 2   | Roller_TPU95A         |

*Insert lots more reading material here *later**

[Buy me a coffee to help keep this project going!](https://buymeacoffee.com/armoredturtle)

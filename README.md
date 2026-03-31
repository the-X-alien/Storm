# Storm | A DIY 3D Printer

<img width="794" height="736" alt="image" src="https://github.com/user-attachments/assets/cfb0a743-1131-4ae0-8a9c-7274dbdfc4f4" />


An open-source Cartesian bedslinger 3D printer built and designed from scratch to beat the Bambu Lab A1 in speed and print quality, by a 13 year old

Most budget 3D printers sacrifice speed for price or quality. Storm is better because it focuses on all three, fast, high quality, and affordability

I used a big Cartesian bedslinger structure + Klipper input shaping + high quality components.

## Goals
- 300–400mm/s print speeds, sub-5min Benchy
- Beat the Bambu Lab A1 in speed and quality
- Under $350 total including shipping and taxes
- Open source
- Screen
- Klipper Firmware
- Cool

## Specs
- Motion system: Cartesian bedslinger
- Build volume 220×220×300mm
- Firmware: Klipper
- Extruder: Sherpa Mini
- Hotend: TZ V6
- Probe: 3DTouch
- MCU: BTT SKR Mini E3 V3.0
- Raspberry Pi Zero 2W
- Display: ILI9341 2.8" SPI touchscreen
- Part Cooling: Dual 5015 blower fans 24V
- Hotend cooling: 4010 axial fan 24V
- Bed: 235×235mm 24V aluminum heated bed (Ender 3 bed) + PEI textured build plate

## Frame
- 4× 2040 aluminum extrusion 350mm for the base
- 2× 2020 aluminum extrusion 350mm for the Z towers
- 1× 2020 aluminum extrusion 350mm for the top crossbar

## Motion
- 8mm smooth linear rods on all axes (X, Y, Z) rails are too expensive :(
- LM8UU linear bearings
- T8 leadscrews 330mm for Z axis
- GT2 6mm belt for X and Y
  
## BOM
https://docs.google.com/spreadsheets/d/1btD1Bjle54Zft8ynW4hvl1bNV1Zsg6aF89J3ntGE-do/edit?usp=sharing

Total: ~$315 before tax and ~$347 with tax

## CAD
assembly in Onshape:
https://cad.onshape.com/documents/37467ea71eb1fca5838973f8/w/7266e1215341462849f7532b/e/d342240afd8f3da62d0e4bb2

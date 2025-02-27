# Fet_C-inline-preamp

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="images/IMG_1.jpg" width="49%" style="margin-bottom: 10px;">
  <img src="images/IMG_2.jpg" width="49%" style="margin-bottom: 10px;">
  <img src="images/IMG_3.jpg" width="49%">
  <img src="images/IMG_4.jpg" width="49%">
</div>

## Project Introduction
Fet_C is a DIY inline preamplifier project utilizing JFETs (Junction Field-Effect Transistors).
This device amplifies signals from low-output dynamic and ribbon microphones to line level.

## Features
- Simple circuit design with minimal component count
- PCB gerber files provided for easy fabrication
- 3D printable case design (STL files included)
- Moderate soldering skills required (includes 4 SMD components)

## Required Materials
- PCB (fabricated using provided gerber files)
- 3D printed case (fabricated using provided STL files)
- NC3FAAH1 [1]
- NC3MAAH-1 [1]
- 2SK209-GR(TE85L,F) [4]
- 1N4148 [2]
- 56Ω 0.1% resistor [1]
- 22KΩ 0.1% resistor [2]
- M3 screws (for case assembly) [4]
- Soldering equipment and materials

**Note**: Most electronic components can be purchased from suppliers such as Digikey.

## Circuit Schematic and PCB Layout
<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="images/diagram.png" width="49%" style="margin-bottom: 10px;">
  <img src="images/pcb.png" width="49%" style="margin-bottom: 10px;">
</div>


## Assembly Tips
- Soldering Order: Start with smaller components, using tweezers for handling. This approach provides easier access to solder points.   
- Additional Shielding: For improved noise reduction, apply aluminum tape to the inside of the case. The PCB features dedicated ground points, and the XLR connectors' screw-mounting points are also connected to ground, enhancing overall shielding effectiveness.   
- Continuity Testing: Before powering on the device, use a multimeter to check for proper connections and to ensure there are no unwanted shorts.   

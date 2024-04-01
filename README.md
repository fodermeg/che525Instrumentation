# che525Instrumentation
2024 CHE 525 Equipment Install

![RHIT Banner](https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/thumbnail_image001.png)

This page provides details on the installation of a Coriolis flowmeter, a hydrostatic pressure transmitter, a radar level transmitter, and a 3-wire RTD.

### Summary of Installed Equipment: 

Tag|Manufacturer|Model|Key Process Parameter
---|:---:|:---:|:---:
FIT525A|Endress+Hauser|Promass F 300, 8F3B08, DN08 3/8"|Flow, Volumetric 
PIT525A|Endress+Hauser|DeltaPilot S FMB70|Pressure, Hydrostatic
LIT525A|Endress+Hauser|Micropilot FMR63B|Level, Radar
TE525A|Omega|3-wire Pt100|Temperature

### Installation Process Steps:
1. Bulid power block on DIN Rail
2. Make EtherNet cable for Coriolis flowmeter
3. Build Charmbox control system with slots for IO cards
4. Add control system to DIN rail
5. Connect control system and power block using DC wires
6. Connect pressure transmitter to control system via DC wires
7. Insert Analog HART IO card into slot where pressure transmitter is connected
8. Test all wiring connecetions with voltage meter
9. Plug power block into 24V DC wall outlet and turn on circut breaker
10. Ensure both controllers have flashing green lights, along with the IO card, and the pressure transmitter display turns on
11. Turn off circut breaker to install rest of equipment
12. Plug one end of EtherNet cable into wall and other end into Coriolis flowmeter
13. Connect Coriolis floweter to power block via DC wires
14. Connect 3-wire RTD to control system via the wires from the instrument (two red - positive and ground, and one black - negative)
15. Instert RTD card into slot on control system where RTD is connected
16. Connect level transmitter to control system via DC wires
17. Insert Analog HART IO card into slot where level transmitter is connected
18. Turn on circut breaker
19. Ensure all three displays (level, pressure, flow) turn on

### Installation Images

###### Pressure Transmitter:
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/pressure%20face.jpg" alt="PT" width="150" height="200">
</p>

###### Level Transmitter:
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/level%20body.jpg" alt="LT Body" width="200" height="150">
</p>
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/level%20face.jpg" alt="LT Face" width="200" height="150">
</p>

###### Coriolis flow meter:
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/flow%20face.jpg" alt="Coriolis flow meter" width="200" height="150">
</p>

###### RTD:
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/RTD.jpg" alt="RTD" width="200" height="150">
</p>

###### Power Block:
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/power%20block.jpg" alt="Power Block" width="200" height="150">
</p>

###### Control System with IO Cards:
<p align="center">
<img src="https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/io%20cards.jpg" alt="Control System" width="200" height="150">
</p>

###### Wiring Overview on DIN Rails:
![Wire Overview](https://raw.githubusercontent.com/fodermeg/che525Instrumentation/main/wiring%20overview.jpg)

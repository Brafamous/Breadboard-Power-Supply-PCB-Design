# Breadboard-Power-Supply-PCB-Design
Welcome to the GitHub repository for my Breadboard Power Supply PCB Design project! This project aims to provide a compact and efficient solution for powering electronic circuits directly on a breadboard. This was design in KiCAD

# Description
A power supply unit (PSU) is a device that converts alternating current (AC) power from an electrical outlet into direct current (DC) power suitable for powering electronic devices. The primary function of a power supply unit is to regulate and provide stable and reliable DC voltage and current to the components it serves. It takes the incoming AC power and transforms it into the appropriate DC voltage levels required by the components, ensuring they receive a consistent power supply. 

Most of the embedded circuits have a standard operating voltage of 5V or 3.3V on the power rails of the breadboard. In this project, I decided to design a power supply which can deliver both either 5V or 3.3V  on the power rails. This project was soley designed using KiCAD.

# Bill of Materials for the Project
| Reference  | Value | Footprint Used |
|----------|----------|----------|
| Capacitor C1 | 10u | Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm |
| Capacitor C2 | 1u | Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm  |
| Capacitor C3 | 0.1u  | Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm |
| Diode D1| LED| LED_THT:LED_D5.0mm |
| Switch J1 | Barrel_Jack_Switch| Connector_BarrelJack:BarrelJack_Horizonta|
| Switch J2, J5| Barrel_Jack_Switch | TerminalBlock:TerminalBlock_bornier-2_P5.08mm |
| Switch J4, J6| Barrel_Jack_Switch | Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical |
| Switch J3, J7| Barrel_Jack_Switch |Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical|
| Resistor R2 | 330 ohms| Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal |
| Resistor R1, R3 | 560 ohms| Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal |
| Slide Switch S1 | EG1218 | Digikey-footprints:Switch_Slide_11.6x4mm_EG1218 |
| U1 | LM317_TO-220 | Package_TO_SOT_THT:TO-220-3_Vertical |
| U2 | LM7805_TO-220 | Package_TO_SOT_THT:TO-220-3_Vertical |


## Schematic


![Schematic]()

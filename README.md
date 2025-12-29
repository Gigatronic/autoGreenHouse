# Automatic Grow Tunnel
This Project is to demonstrate a A-Z DIY build of a green house. The goal of this project is to
1. Buy The electrical components, including wires, PCB boards , breakers.
2. Buy components to make a IP66/67 complient setup. A IP67 complient setup is a must in a greenhouse environment.
3. Buy a water pump and solinoid valves which are controlled by the electrical components.
4. Buy a grow tunnel, water pipes, sprinklers and 
5. Make a electrical diagram which shows the electrical wiring using the easyda.com free online tool for diagrams.
6. Make a 3D cad model of the setup to show the dimensions of the different components are correct.
7. Build the solution.
8. Program the the computer chip with RUST to control the watering based on input sensors and stream the data with wifi to the house.

## The electrical components required:
1. Custom bord (See PCB file)
3. LED Transformer 1-18 W, 240 V to 12 V Driver Power Supply, No LED Flicker, No Transformer Noise, LEDs Low Voltage Transformer, for G4, MR11 GU4, MR16 GU5.3 LEDs Light Strips, Pack of 1              amazon.de
4. Schneider automatsikring C Resi9 XP, 1P+0, 13A (https://www.lavprisel.dk/schneider-automatsikring-c-resi9-xp-1p0-13a-526058)
5. 2 x Aideepen 6 Pieces Soil Moisture Sensor Hygrometer Module V1.2 Capacitive Corrosion Resistant Module for Plant Watering DIY Kits     amazon.de   ( € 9)
6. Electric Potting Compound Electronics Transparent Insulating Paint Radiator Paint Conformal Coating, Waterproof, Heat Resistant, Suitable for Circuit Boards and Control Boards, 100 ml amazon.de €13.23

## Mechanical Components
1. EYPINS Waterproof distribution box, IP67, junction box, waterproof ABS plastic housing, outdoor socket box, switch box, power box with mounting accessories, 30 x 20 x 16 cm, grey control cabinet (amazon.de) €33.60
2.320PCS M3 Male Female Nylon Hex Spacer Standoff Screw Nut Threaded Pillar PCB Motherboard Assorted Assortment Kit (Black)              (amazon.de)             €13.65
3.  8 x 12 V Normally Closed Quick Insert Inlet Water Solenoid Valve for Pure Water Machine Water Dispenser Washing Machine(amazon.de) €80
4. Retoo Mini Water Pump 12 V, Submersible Aquarium Pump 240 L/H 4.8 W, Brushless Small Submersible Pump, Fountain Pump, Centrifugal Pump, Nozzle Diameter 8 mm, Without Plug (amazon.de) €8.60                         
5. 48-Piece 8 mm Pneumatic Quick Push-in Connection Kit for Air Hoses, Hose OD Push to Connect Air Control Ball Valve Pneumatic Valve Union (18 x Straight/10 x Angle/10 x T-/10 x Splitter) (amazon.de)  €12.49
6. QWORK® 10m PU Pneumatikschlauch Außen 8mm x Innen 5mm Blau, Flexibel Druckluftschlauch für Pneumatische Werkzeuge     (amazon.de)    € 32
7. Hose Clamps Pack of 10, Hose Clamp, 8 Size Adjustable Brake Hose Clamp for Clamping, 6 mm - 20 mm, Stainless Steel Worm Drive Hose Clamp for Home, Gas Pipe, Flexible Hose Pipe (6-8 mm) €8
8. Pack of 50 Garden Hose Mounting Anchors, 360 Degree Irrigation System, Micro Drip Drip, 8 Holes Sprinkler, Socket Fork for 4/7 mm Hose, Drip Irrigation Emitters (Black) €19
9. EYPINS Waterproof distribution box, IP67, junction box, waterproof ABS plastic housing, outdoor socket box, switch box, power box with mounting accessories, 15 x 15 x 9 cm, transparent control cabinet €20
## Green House Components
1. VEVOR Walk-in Tunnel Drivhus, 20 x 10 x 7 ft bærbart plantevarmehus m/ galvaniserede stålbøjler, 3 topbjælker, 4 diagonale pæle, 2 lynlåsdøre og 12 rullevinduer, hvid https://eur.vevor.com/greenhouse-c_11889/vevor-walk-in-tunnel-greenhouse-galvanized-frame-waterproof-cover-20x10x7-ft-p_010650738220
2. 8 x Højbedsramme sortbejdset 19 mm, 120 x 80 x 20 cm    https://www.jemogfix.dk/hoejbedsramme-sortbejdset-19-mm-120-x-80-x-20-cm/2193/9036005/

## Wiring components

3. 20 m   Multikabel LIYY 2x0,75 mm² uskærmet           https://www.lavprisel.dk/multikabel-liyy-2x075-mm2-uskaermet-68266
3. 20 m   Multikabel LIYY 3x0,50 mm² uskærmet            https://www.lavprisel.dk/multikabel-liyy-3x05-mm2-uskaermet-68279
9. 8 x Forskruning M20, Ø6-12 mm, IP68                    https://www.lavprisel.dk/forskruning-m20-oe6-12-mm-ip68-53937
10. 40 stk Multipakning til M20 forskruning 3x4 mm        https://www.lavprisel.dk/multipakning-til-m20-forskruning-3x4-mm-634747

# 3D model of the setup.
The greenhouse with all components are modelled using https://www.freecad.org/ version 1.0 software. The modelling is done using the IEC standard:
IEC 60204-1 — Safety of Machinery: Electrical Equipment
IEC 61439-1 / 2 — Low-voltage Switchgear and Controlgear Assemblies
IEC 60364 — Electrical Installations of Buildings
EN 60730 / IEC 60730 — Automatic Electrical Controls

## Electrical Drawings
The electrical drawings for the setup has beeen done by using EasyEDA. You can get a free account provided that the schematics are open source. The schematics can be found in the PDF file.
The drawings contain a circuirt breaker and residuel current for current overflow to comply with IEC standards:
        1.  IEC 60898-1 Electrical accessories – Circuit-breakers for overcurrent protection for household and similar installations
        2.  Leakage protection (RCD / RCBO) IEC 61009-1

## 3D model of box
The high powered AC 240 Volts is 



# Thermal appoximations of setup.
The heat distrubtion inside the box is modelled using https://wiki.freecad.org/FEM_Workbench to model the temperature inside the box.


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
3. LED Transformer 1-36 W, 240 V to 12 V Driver Power Supply, No LED Flicker, No Transformer Noise, LEDs Low Voltage Transformer, for G4, MR11 GU4, MR16 GU5.3 LEDs Light Strips          amazon.de €8.91
4. Schneider automatsikring C Resi9 XP, 1P+0, 13A (https://www.lavprisel.dk/schneider-automatsikring-c-resi9-xp-1p0-13a-526058)
5. 2 x Aideepen 6 Pieces Soil Moisture Sensor Hygrometer Module V1.2 Capacitive Corrosion Resistant Module for Plant Watering DIY Kits     amazon.de   ( € 9)
6. Electric Potting Compound Electronics Transparent Insulating Paint Radiator Paint Conformal Coating, Waterproof, Heat Resistant, Suitable for Circuit Boards and Control Boards, 100 ml amazon.de €13.23

## Mechanical Components
1. EYPINS Waterproof distribution box, IP67, junction box, waterproof ABS plastic housing, outdoor socket box, switch box, power box with mounting accessories, 30 x 20 x 16 cm, transparent control    (amazon.de)  €33.60
2  YIXISI Pack of 280 M3 Nylon Male-Female Hex Column Standoff Spacer Screw Nut Assortment Kit for Board Repair Accessories, Black          (amazon.de)             €8.39
3. 4 x 2pcs DC 12V 4.8W Mini Brushless Submersible Pump Water Pump Centrifugal Pump 240L/H Aquarium Garden Fall Fish Container Water Fountain Entertainment Nozzle Diameter 8 mm for Pool Aquarium Fish Tank  (amazon.de)   €44          
4. Forever Speed Irrigation System 315 Pieces Garden Irrigation Kit, 60 m + 15 m Irrigation Pipes, Drip Irrigation Spray Irrigation Cooling System for Landscape, Greenhouse, Patio  (amazon.de)    €32.55
7. 60-Piece Professional Hose Clamp Set, 8-38 mm Pipe Clamps Made of 304 Stainless Steel, 7 Sizes Hose Clamps, Hose Ties Industrial Quality, Robust for Water Pipes, Automotive Tubing  (amazon.de)  €13.65
8. Hailege 2pcs CP2102 USB 2.0 to TTL UART Serial Converter Module 5-Pin STC PRGMR with Dupont Wire  (amazon.de) €9.65
9. WEILAOK Electronics Insulating Spray, Transparent Insulating Varnish, Waterproof and Quick Drying, Suitable for Circuit Boards and Control Boards of Household Appliances, 100 ml €13.43

## Green House Components
1. VEVOR Walk-in Tunnel Drivhus, 20 x 10 x 7 ft bærbart plantevarmehus m/ galvaniserede stålbøjler, 3 topbjælker, 4 diagonale pæle, 2 lynlåsdøre og 12 rullevinduer, hvid https://eur.vevor.com/greenhouse-c_11889/vevor-walk-in-tunnel-greenhouse-galvanized-frame-waterproof-cover-20x10x7-ft-p_010650738220
2. 8 x Højbedsramme sortbejdset 19 mm, 120 x 80 x 20 cm    https://www.jemogfix.dk/hoejbedsramme-sortbejdset-19-mm-120-x-80-x-20-cm/2193/9036005/

## Wiring components

3. 20 m   Multikabel LIYY 2x0,75 mm² uskærmet           https://www.lavprisel.dk/multikabel-liyy-2x075-mm2-uskaermet-68266
3. 20 m   Multikabel LIYY 3x0,50 mm² uskærmet           https://www.lavprisel.dk/multikabel-liyy-3x05-mm2-uskaermet-68279
9. 16 x Forskruning M16 Polyamid IP68                   https://www.lavprisel.dk/forskruning-m16-polyamid-ip68-73570

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


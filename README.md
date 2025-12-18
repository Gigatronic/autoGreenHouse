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
Optokobler Relæ 1-Kanal 12V LOW/HIGH Module     (https://ardustore.dk/produkt/optokobler-relae-1-kanal-12v-low-high-module)
Optokobler Relæ 8-Kanal 12V LOW/HIGH Module     (https://ardustore.dk/produkt/optokobler-relae-8-kanal-12v-low-high-module)
Strømforsyning 230V – 12V 20A                    https://ardustore.dk/produkt/led-driver-transformer-230v-12v-5a
Schneider automatsikring C Resi9 XP, 1P+0, 13A (https://www.lavprisel.dk/schneider-automatsikring-c-resi9-xp-1p0-13a-526058)
8 x Jord Hygrometer Fugtighedsmåler Module      (https://ardustore.dk/produkt/soil-moisture-modul-sensor)
DC-DC Step-Down LM2596 Converter Module Display (https://ardustore.dk/produkt/dc-dc-step-down-lm2596-converter-module-display)
NodeMcu ESP32S 38Pin CH340G Udviklingsboard     (https://ardustore.dk/produkt/nodemcu-esp32s-38pin-ch340g-udviklingsboard)
        

## Mechanical Components
Montagekasse EKOE MPI 130 T 280x280 mm m/klart låg og mont.plade https://www.lavprisel.dk/montagekasse-ekoe-mpi-130-t-280x280-mm-mklart-laag-og-montplade-752870
M3 x 20MM Afstands Forlænger Sortiment kasse 300Stk. https://ardustore.dk/produkt/m3-x-20mm-afstands-forlaenger-sortiment-kasse-300stk
8x Plastic Water Solenoid Valve - 12V - 1/2" Nominal https://www.kiwi-electronics.com/en/plastic-water-solenoid-valve-12v-1-2quot-nominal-2624?search=Solenoi
Water Pump - 8mm - 5-12VDC                           https://www.kiwi-electronics.com/en/water-pump-8mm-5-12vdc-11105?search=pump
20MM Afstands Forlænger Sortiment kasse     https://ardustore.dk/produkt/m3-x-20mm-afstands-forlaenger-sortiment-kasse-300stk

## Green House Components
VEVOR Walk-in Tunnel Drivhus, 20 x 10 x 7 ft bærbart plantevarmehus m/ galvaniserede stålbøjler, 3 topbjælker, 4 diagonale pæle, 2 lynlåsdøre og 12 rullevinduer, hvid https://eur.vevor.com/greenhouse-c_11889/vevor-walk-in-tunnel-greenhouse-galvanized-frame-waterproof-cover-20x10x7-ft-p_010650738220
Højbedsramme sortbejdset 19 mm, 120 x 80 x 20 cm    https://www.jemogfix.dk/hoejbedsramme-sortbejdset-19-mm-120-x-80-x-20-cm/2193/9036005/

## Wiring components
3 xHolder u/aflastning 5-vejs t/Inline samlemuffe, skruemont., grå https://www.lavprisel.dk/holder-uaflastning-5-vejs-tinline-samlemuffe-skruemont-graa-241343
3 xSamlemuffe 10x0,2-4 mm² transparent med orange pal, serie 221 Wago https://www.lavprisel.dk/samlemuffe-10x02-4-mm2-transparent-med-orange-pal-serie-221-753035
20 m   Multikabel LIYY 2x0,75 mm² uskærmet           https://www.lavprisel.dk/multikabel-liyy-2x075-mm2-uskaermet-68266
20 m   Multikabel LIYY 3x0,50 mm² uskærmet           https://www.lavprisel.dk/multikabel-liyy-2x075-mm2-uskaermet-68266](https://www.lavprisel.dk/multikabel-liyy-3x05-mm2-uskaermet-68279
UL-1007 Flexible Ledning AWG-24 0.20# – Blå (ground)  https://ardustore.dk/produkt/ul-1007-flexible-ledning-awg-24-0-20-blaa
UL-1007 Flexible Ledning AWG-24 0.20# – Sort (signal)        https://ardustore.dk/produkt/ul-1007-flexible-ledning-awg-24-0-20-sort
UL-1007 Flexible Ledning AWG-24 0.20# – Rød (strø¨m)         https://ardustore.dk/produkt/ul-1007-flexible-ledning-awg-24-0-20-roed 
8 x Forskruning M20, Ø6-12 mm, IP68                    https://www.lavprisel.dk/forskruning-m20-oe6-12-mm-ip68-53937
40 stk Multipakning til M20 forskruning 3x4 mm        https://www.lavprisel.dk/multipakning-til-m20-forskruning-3x4-mm-634747

# 3D model of the setup.
The greenhouse with all components are modelled using https://www.freecad.org/ version 1.0 software. The modelling is done using the IEC standard:
IEC 60204-1 — Safety of Machinery: Electrical Equipment
IEC 61439-1 / 2 — Low-voltage Switchgear and Controlgear Assemblies
IEC 60364 — Electrical Installations of Buildings
EN 60730 / IEC 60730 — Automatic Electrical Controls

## 3D model of box
The high powered AC 240 Volts is 



# Thermal appoximations of setup.
The heat distrubtion inside the box is modelled using https://wiki.freecad.org/FEM_Workbench to model the temperature inside the box.


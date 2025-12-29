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
3. Strømforsyning 230V – 12V 5A                    https://ardustore.dk/produkt/led-driver-transformer-230v-12v-5a
4. Schneider automatsikring C Resi9 XP, 1P+0, 13A (https://www.lavprisel.dk/schneider-automatsikring-c-resi9-xp-1p0-13a-526058)
5. 8 x Jord Hygrometer Fugtighedsmåler Module      (https://ardustore.dk/produkt/soil-moisture-modul-sensor)        

## Mechanical Components
1. Montagekasse EKPE MPI 130 G 380x280 mm m/gråt låg og mont.plade https://www.lavprisel.dk/montagekasse-ekpe-mpi-130-g-380x280-mm-mgraat-laag-og-montplade-752866
2. M3 x 20MM Afstands Forlænger Sortiment kasse 300Stk. https://ardustore.dk/produkt/m3-x-20mm-afstands-forlaenger-sortiment-kasse-300stk
3. 8x Plastic Water Solenoid Valve - 12V - 1/2" Nominal https://www.kiwi-electronics.com/en/plastic-water-solenoid-valve-12v-1-2quot-nominal-2624?search=Solenoi
4. Water Pump - 8mm - 5-12VDC                           https://www.kiwi-electronics.com/en/water-pump-8mm-5-12vdc-11105?search=pump
5. IQ haveslange 25 m 1/2"                              https://www.lavprisvvs.dk/iq-haveslange-25-m-12-1001328222
6. 8x Waving messing T-stykke, 1/2"                     https://www.lavprisvvs.dk/wavin-messing-t-stykke-12-1000052456
7. 16 x Worker hanekobling med gevind 1/2"              https://www.lavprisvvs.dk/worker-hanekobling-med-gevind-12-508532
8. 8 x Gardena 6-i-1 sprøjtedyse                        https://www.lavprisel.dk/gardena-6-i-1-sproejtedyse-754685
9  2 x Wavin fordelerrør 3/4", 4 afgreninger 1/2"       https://www.lavprisvvs.dk/wavin-fordelerroer-34-4-afgreninger-12-1000257637
10. 8 Spændebånd, 16-22 mm, rustfri                     https://www.lavprisvvs.dk/spaendebaand-16-22-mm-rustfri-200365#product-description
11. Messing prop, 3/4"                                  https://www.lavprisvvs.dk/messing-prop-34-191074
         
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


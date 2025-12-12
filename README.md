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
Strømforsyning 230V – 12V 20A                   (https://ardustore.dk/produkt/stroemforsyning-230v-12v-20a)
8 x Jord Hygrometer Fugtighedsmåler Module      (https://ardustore.dk/produkt/soil-moisture-modul-sensor)
DC-DC Step-Down LM2596 Converter Module Display (https://ardustore.dk/produkt/dc-dc-step-down-lm2596-converter-module-display)
NodeMcu ESP32S 38Pin CH340G Udviklingsboard     (https://ardustore.dk/produkt/nodemcu-esp32s-38pin-ch340g-udviklingsboard)
        

## Mechanical Components
Montagekasse EKOE MPI 130 T 280x280 mm m/klart låg og mont.plade https://www.lavprisel.dk/montagekasse-ekoe-mpi-130-t-280x280-mm-mklart-laag-og-montplade-752870
M3 x 20MM Afstands Forlænger Sortiment kasse 300Stk.

## Wiring components
Wago samlemuffe i gul 5x0,5-2,5 mm² https://www.lavprisel.dk/wago-samlemuffe-5x4-mm2-transparent-53887
Fastgørelsesadapter til 5-lederklemmer Wago https://www.lavprisel.dk/fastgoerelsesadapter-til-5-lederklemmer-wago-221-4-mm2-hvid-248606
20MM Afstands Forlænger Sortiment kasse     https://ardustore.dk/produkt/m3-x-20mm-afstands-forlaenger-sortiment-kasse-300stk

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


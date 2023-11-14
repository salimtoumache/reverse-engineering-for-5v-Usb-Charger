# reverse-engineering-for-5v-Usb-Charger

I was sitting looking at a 5v charger and thought to myself why not reverse engineer it !!! This is my first reverse engineering

## TOP:


![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/TOP.jpeg)

## BOTTOM:


![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/BOTTOM.png)



I traced the paths using a multimeter, then extracted the circuit diagram. As shown in the following figure

![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/SCH1.jpeg)

![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/SCH2.jpeg)


# 1.Schematic

I drew the circuit diagram on KICAD


![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/SCH.jpeg)


# 2.Layout


I set all component footprint I only found a problem with the transformer (EE10 Voltage Transformer smps) I designed it again by measuring the diameters of the pins in it and taking all its dimensions


![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/BOM.jpeg)


Finally I routed the PCB tracks


![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/LAYOUT1.jpeg)
![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/LAYOUT2.jpeg)
![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/LAYOUT3.jpeg)

# 3.3D

## TOP:

![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/2.jpeg)
![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/4.jpeg)
## BOTTOM:
![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/1.jpeg)
![App Screenshot](https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCREEN/3.jpeg)

# Assembly Files

- Bom file : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/ASSEMBLY/BOM/BOM.csv
- Gerber file : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/tree/main/EX/ASSEMBLY/GERBER
- POS file : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/ASSEMBLY/POS/POS.csv
- Sch file : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/tree/main/EX/ASSEMBLY/SCH
  
# Documentation

https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/DOC/Pcb%20Reverse%20Engineering.pdf

# Design
- Layout : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/LAYOUT/LAYOUT.pdf
- Sch : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/blob/main/EX/SCH/SCH.pdf
- Screen : https://github.com/salimtoumache/reverse-engineering-for-5v-Usb-Charger/tree/main/EX/SCREEN

# Contact us

- EMAIL : salimtoumache@gmail.com
- PHONE : +213552892780
- LINKEDLN : https://www.linkedin.com/in/salim-toumache-8a060b176/
- IG : https://www.instagram.com/salim_toumache/
- FB : https://www.facebook.com/salim.toumache.5



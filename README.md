# SonoffIR
Sonoff IR remote controll extension
## Schematics
![Schematics](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR-Schematics.png)
The resistor values depend on the used IR LED and the gain of the NPN Transistor. Rb is not really necesarry an can be left out. R1 limits the current through the diod and can have Values between 2.5 Ohm and 10 Ohm. Using lower values gives you a better range but you risk the diod if the current gets to high. About 100mA are ok for sending signals.
## Board layout
![Board](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR-Board.png)
The Diod is facing upwards, the rest downwards. The board directly fitts onto the Sonoff Pinheader used for programming and uses GPIO14.
## Assembly
![Parts](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR-parts.jpg)
![Board](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR-board.jpg)
![Fitted](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR-fitted.jpg)
![Chassis](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR-chassis.jpg)
![SonoffIR](https://raw.githubusercontent.com/altelch/SonoffIR/master/SonoffIR.jpg)

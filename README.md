﻿ LiquidCrystal lcd(7, 6, 5, 4, 3, 2);           //RS,E,D4,D5,D6,D7

# Ardutester
ArduTester – Arduino Component Tester

This is an Arduino porting of the excellent work by Markus Frejek.

The Ardutester software is based on porting by Markus Reschke (madires@theca-tabellaria.de)

The final aim is to create an economic component tester using Arduino and a few passive components; 
I’m trying to make the system more scalable as possible, so you can view the output in Serial Terminal or alternatively via a I2C LCD.

I’m working on a shield which will also include the components for the Logic Analyzer (Another project of ABC). For my convenience i publish first SMD version and then TH Version.

This is the basic design:

![alt tag](https://github.com/kr4fty/Ardutester/blob/master/disp35e1.png)

# RPiAOneI2cSensors
Printed circuit board for Raspberry Pi (TM) for connecting external I2C 
sensors using modular 4P4C connectors. Breakout boards from Adafruit and 
Sparkfun can be wired for testing. By soldering 20 pins female header on 
the board the I2C modules can be re-used in an other project or connected 
with cable using the 4P4C modular connectors. 

NOTE: Careful soldering is needed when using the board. Double check the 
connections since short circuit on power supply lines can damage the
Raspberry Pi permanently. Multimeter is handy when checking the wiring.

Parts
=====

```textile
D1,D2         zener 3V3        
J1,J2,J3      4P4C modular        
JP1           jumper      
P0            2x20 pins female header
              20 pins female header (not shown on diagram)
R1,R2         100 ohm        
VR1           Resettable Fuse PPTC 1206 60V 0.05A       
```

Files
=====

```textile
README.md                         - this file
RPiAOneI2CSensors-B_Cu.pdf        - back copper
RPiAOneI2CSensors-B_Cu.gbl        - back copper Gerber file
RPiAOneI2CSensors-B_Mask.gbs      - bottom solder stop mask
RPiAOneI2CSensors-F_Cu.pdf        - top copper
RPiAOneI2CSensors-F_Cu.gtl        - top copper
RPiAOneI2CSensors-F_Mask.gts      - top solder stop mask
RPiAOneI2CSensors-F_SilkS.pdf     - top silk screen
RPiAOneI2CSensors-F_SilkS.gto     - top silk screen Gerber file
RPiAOneI2CSensors.drl             - drill file
RPiAOneI2CSensors-NPTH.drl        - drill file
RPiAOneI2CSensors.pdf             - circuit diagram
RPiAOneI2CSensors.sch             - circuit diagram
```


# RPiAOneI2cSensors
PCB for Raspberry Pi for connecting external I2C sensors using modular 4P4C
connectors. HTU21D and BMP180 are on the same board. The board is one sided
with 9 jumper wires for easier home production.

NOTE: The breakout board pin order may change with different versions. 
Check first that the adapter board in this repository is suitable for the
version of the breakout board you are using.

Parts
=====

```textile
D1,D2         zener 3V3        
J1,J2,J3      4P4C modular        
JP1           jumper      
P1            40 pins female header
R1,R2         100 ohm        
U1            Sparkfun HTU21D 
U2            Adafruit BMP180  
VR1           polyfuse 100 mA (or smaller)       
```

Files
=====

```textile
README.md                         - this file
RPiAOneI2CSensors-B_Cu.pdf        - back copper
RPiAOneI2CSensors-B_Cu.pho        - back copper Gerber file
RPiAOneI2CSensors-F_SilkS.pdf     - top silk screen
RPiAOneI2CSensors-F_SilkS.pho     - top silk screen Gerber file
RPiAOneI2CSensors-NPTH-drl_map.pho - drill map Gerber file
RPiAOneI2CSensors-NPTH.drl        - drill file
RPiAOneI2CSensors-drl_map.pho     - drill map Gerber file
RPiAOneI2CSensors.drl             - drill file
RPiAOneI2CSensors.lst             - component list
RPiAOneI2CSensors.pdf             - circuit diagram
RPiAOneI2CSensors.sch             - circuit diagram
```


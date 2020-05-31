# FX10A-168 MCU Card Template #

KiCAD libraries, schematic and layout to get you started creating open source hardware.

### Connectors ###

CON1: [Hirose FX10A-168P-SV(71)](https://www.hirose.com/product/p/CL0570-0044-8-71?lang=en)

CON2: [Hirose FX10A-168S-SV](https://www.hirose.com/product/p/CL0570-0244-7-00?lang=en)

### Schematic ###

Note: schematic symbols are representative of geometric arrangement of pins. The convention in the libraries is in analogy to the [Myriad-RF connector specification](https://wiki.myriadrf.org/RFDIO) and common dual-row pin headers. Libraries supplied with this design have been compiled from different sources and modified for consistency.

![schematic view](doc/20200531_sch.png)

### Board ###

Note: The connector pitch has been set to 50.9 mm. According to [datasheet specifications](http://www.farnell.com/datasheets/2691101.pdf), a maximum position error of +/-0.3 mm in the XY-plane is acceptable for a board with mutiple connectors, which needs to cover NPTH drill tolerance and the loose fit of the locating pegs on top of any potential design mismatch to a motherboard in question, so check whether the pitch needs to be 50.8 mm, 51.0 mm or something else. 

![layout view](doc/20200531_board.png)

![layout view](doc/20200531_render_i.png)

### Disclaimer ###

Files in this project are provided as-is. No responsibilities for damage or harm caused by its use will be accepted.
Corrections and suggestions are always welcome. 

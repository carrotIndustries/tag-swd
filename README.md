ST-LINK/V2 Tag-Connect adapter
==============================

Adapter board for connecting the 6-pin Tag-Connect [TC2030-IDC](https://www.tag-connect.com/product/tc2030-idc-6-pin-tag-connect-plug-of-nails-spring-pin-cable-with-legs)
cable to an ST-LINK/V2. There's the 
[ARM20-CTX](https://www.tag-connect.com/product/arm20-ctx-20-pin-to-tc2030-idc-adapter-for-cortex) adapter
from Tag-Connect, but it's kinda expensive and poor mechanical fit for 
ST-LINK/V2 with its vertical connector, so I made my own based on the 
[Hubble SWD 
adapter](https://github.com/carrotIndustries/hubble/#swd-debug-adapter). Pin mapping is identical to the ARM20-CTX.

As usual, this board is made with [Horizon EDA](https://horizon-eda.org/).

![Photo of an ST-LINK/V2 lying on wooden surface with a d-shaped 
adapter board plugged in. On the adapter, board there's a 6-pin IDC 
connector that's connected to a Tag-Connect cable.](photo.jpg?raw=true)

# BOM

 - [SFH11-PBPC-D10-ST-BK](https://www.digikey.de/en/products/detail/sullins-connector-solutions/SFH11-PBPC-D10-ST-BK/1990090) for the 20 pin connector
 - Generic 6 Pin 2.54mm IDC header

# License

CERN Open Hardware Licence v1.2

# See also

[Similar idea, but better suited for programmers with horizontal connector ](https://github.com/Jana-Marie/JlinkBreakout)

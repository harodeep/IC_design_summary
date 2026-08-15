# Op amp design
this branch contains the schematic , design , AC simulation analysis of a two stage operational amplifier designed in 180nm tech in cadence
Supply voltage =1.8V
DC gain = 70dB
phase margin=67 degree
GBW / UGB = 20MHz
here is the schematic for it <img width="1174" height="373" alt="image" src="https://github.com/user-attachments/assets/9fdd8fe8-373f-45f1-9940-4d3616bed9fe" />
here is the test bench for the same <img width="1175" height="372" alt="image" src="https://github.com/user-attachments/assets/1c037912-8884-4575-9b5d-b4daf049c0f0" />
The architecture employs a differential amplifier input stage followed by a common-source gain stage with pole-splitting Miller compensation to guarantee stability under closed-loop feedback.
the key aspect ratios are as follows differential pair - NMOS - 3 , PMOS - 11. the tail current NMOS aspect ratio 11 , aspect ratio for 2nd stage PMOS-108 , aspect ratio for 2nd stage NMOS-55 , output stage capacitor - 2pF , compensating capacitor 800fF
Simulation for this circuit <img width="495" height="366" alt="op amp ac" src="https://github.com/user-attachments/assets/dadfdce2-ed5a-4785-b8f4-f6aa46a7f70b" />

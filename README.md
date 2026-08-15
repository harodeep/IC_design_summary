# Ring Oscillator (180 nm CMOS)
This repository contains design , schematic capture and transient simulation of a 3 stage ring oscillator design
Supply Voltage 1.8V
Rise Time 330ps
Fall time  300ps
Frequency 500MHz
This circuit has a really simple architecture , it has three inverters with a capacitive load connected in series and the output of the last inverter is the input of the first inverter.
Here is the schematic for the same <img width="1175" height="397" alt="image" src="https://github.com/user-attachments/assets/92efca71-3266-4e84-9d54-33b460c8af22" />
Here are the key design variables W/L of NMOS = 4, W/L of PMOS = 16, value of capacitive load = 68fF
Simulation results for the same <img width="495" height="366" alt="ring oscillator" src="https://github.com/user-attachments/assets/00cec47b-124d-4b72-9f3d-703169043641" />
transient response <img width="495" height="366" alt="ring oscillator transient" src="https://github.com/user-attachments/assets/91e8d0a2-beac-412e-9d0b-b6e4b20cb4c9" />


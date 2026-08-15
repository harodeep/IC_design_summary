# Bandgap Reference Design 
this repo contains the design , schematics and temperature variation simulation of a BGR circuit
this is a BGR circuit based on a basic op amp and resistor based architecture.it doesnt include a startup circuit instead the simulation uses node set as a convergence aid.
here is the schematic <img width="1176" height="398" alt="image" src="https://github.com/user-attachments/assets/2575937f-8322-4fb5-a23e-0663d1240070" />
and here is the temperature varying dc simulation for the same where i have achieved a bell shaped curve which is desired for this circuit <img width="996" height="362" alt="bgr_basic" src="https://github.com/user-attachments/assets/9d0c3506-4f7b-4f90-880d-30800a10196e" />
for one branch i used 1 pnp , transistor for the other branch i used 8 pnp transistors and the resistance values for this branch is 850 and 8.3kohm respectively while the branch connected to 1 transistor uses a 8.3kohm resistor.

# D flip flop design
Here is the design , schematic capture  , transient analysis of a D flip flop
Supply voltage = 1.8V
setup time = 0.5ns
clk to q delay =1.5ns 
this circuit has a master slave , positive latch , negative latch based flip flop architecture. It uses a 2:1 MUX based transmission gate logic to create this latch.
here is the schematic for it <img width="1175" height="367" alt="image" src="https://github.com/user-attachments/assets/2b16dfa0-bfdf-4558-8ea8-5a91bf7dccf8" />
it uses the ring oscillator in previous experiment for clk generation ,to make the clock have sharper edges we use an inverter with no capacitive load. It uses transmission gate logic.
here is the simulation for it <img width="495" height="366" alt="d flip flop" src="https://github.com/user-attachments/assets/669c8ce6-5f8a-4638-939b-1dfd8f530086" />

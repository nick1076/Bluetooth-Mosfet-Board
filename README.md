# Bluetooth Mosfet Board
 Schematic, Code, and Documentation for a Bluetooth-controlled Mosfet board I am developing.

 ## Status
The Bluetooth Mosfet Board is currently still under development and I am currently focused on developing the custom PCB for the hardware. From there I will develop the software portion.

# Documentation

## Developing the PCB

To begin I drew up the schematic of the board I had in mind within KiCad. This board will be managed by an ATtiny 1614 microcontroller and will include a power indicator light, a heartbeat or code-based indication light, and of course a Mosfet (Thinking IRF510N). There will be SMD horizontal headers used to program and power the device, and also to jump certain outputs over to the Bluetooth board, which I am planning to us an HC-05 or HC-06 for.

## Routing Traces

After designing the PCB by laying out the schematic, I moved on to plot and route traces and componets as they would actually be milled on the board. I did so once again in KiCad and with some minor adjustments to the initial schematic I was able to get everything to route perfectly without the need for any jumps or 0 ohm resistors. The board from here can be milled and tested once software is developed.

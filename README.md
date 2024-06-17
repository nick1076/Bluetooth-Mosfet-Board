# Bluetooth Mosfet Board
 Schematic, Code, and Documentation for a Bluetooth-controlled Mosfet board I am developing.

 ## Status
The Bluetooth Mosfet Board is currently still under development and I am currently focused on developing the custom PCB for the hardware. From there I will develop the software portion.

# Documentation

## Developing the PCB

To begin I drew up the schematic of the board I had in mind within KiCad. This board will be managed by an ATtiny 1614 microcontroller and will include a power indicator light, a heartbeat or code-based indication light, and of course a Mosfet (Thinking IRF510N). There will be SMD horizontal headers used to program and power the device, and also to jump certain outputs over to the Bluetooth board, which I am planning to us an HC-05 or HC-06 for.

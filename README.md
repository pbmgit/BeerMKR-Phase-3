# BeerMKR-Phase-3
This repository is supposed to contain the elements, compatible with each other, to assemble a post AWS BeerMKR

Phase 3 BeerMKR is a design that uses a specific Arduino board that has a beefed up voltage regulator and a serial connection on the card that can be used instead of USB.  The design has and interface board that matches this configuration for the BeerMKR to plug into and a Raspberry Pi Zero 2W can plug onto it to control the recipe.

The design is a 4 board stack.  From bottom to top it is: Arduino Mega 2560 (Specifically the KeyEStudio Mega Plus 2560), A RAMPS 1.6 board which is a 3D printing board designed to plug on top of the Arduino, then the BeerMKR interface board plugs on that, then the Pi is either soldered or plugged (TBD) on top of that board.


Directory Collections

Interface contains the KiCAD circuit diagram and hopefully the PC board information for the Arduino to BeerMKR Connections
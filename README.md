# Description

Simple lamp to host a flexible 8x32 LED's matrix. Combined with correct hardware and software it can be controlled from self phone and get some cool effects.

# LEDs matrix

Used a flexible 8x32 LEDs matrix. Dimensions: 317.5mm x 81mm x 2.5mm

# Power supply

There is a hole to put a 5.5mm 2.1mm female jack for power supply. I used a 5v 3Amps one, but it depends on your LEDś matrix specifications.

# Hardware/Software

I have connected the led matrix to an ESP8266 (NodeMCU in my case) with WLED on it. If ESP32 is used I would suggest to use this WLED (Noise reactive) that support 2d matrix in a better way.

# Light diffuse

Two things have been made to get a good diffusion. 

* Add distance between the LEDs matrix and the diffuse screen
* Add a diffuse screen

This configuration worked fine for me with white PLA. I have also tested transparent PLA but I only got vertical diffusion, what is also cool, but not what I was looking for.

# Assembly instructions

There are only 3 parts, and there are grooves in both the top and the bottom part to put the LEDs matrix and the diffuse screen. The diffuse screen helps to keep everything in place

The pieces have been designed to fit, however, I had elephant foot issues with the diffuse screen and I needed cut it to make it thinner.

Assembly steps:

* Screw the power supply jack to the bottom piece
* Put the LEDs matrix in the top piece internal groove
* Put the diffuse screen in the  top piece external groove
* Put the bottom piece
* Connect wires (power supply, led matrix, and whatever hardware used to control the LEDs)
* Power it!!!

# LINKS

https://www.printables.com/model/217568-led-matrix-lamp

# TODO

Close the bottom piece. It is very convenience to have it open to connect all wires, but it will be great to have a lid to close it.

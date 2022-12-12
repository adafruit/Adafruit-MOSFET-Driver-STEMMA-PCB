## Adafruit Adafruit MOSFET Driver STEMMA PCB

<a href="http://www.adafruit.com/products/5648"><img src="assets/5648-04.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Adafruit MOSFET Driver STEMMA. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5648

### Description

Sparky the Blue Smoke Monster shows up whenever the magic smoke is let of of an electronic component. And his very favorite is whenever folks first start with electronics and robotics: wiring up a motor or solenoid or high power LED is a perfect recipe for getting that blue smoke out of an Arduino or Raspberry Pi. Why? Because these high-current devices can't be connected directly to a GPIO pin on a microcontroller! They need to have a transistor / MOSFET driver, plus a kickback-protection diode that will absorb the inductive 'kick' caused by turning on-and-off motors and solenoids. Without that driver and diode - your tronix will go poof!

We have tutorials on how to wire up the components to create a transistor driver on a breadboard, but its easy to put the diode in backwards, or pick the wrong kind of transistor. And some folks don't want to have the extra breadboard for just controlling a simple motor fan or solenoid. Which is why we designed the Adafruit STEMMA MOSFET Driver for Motors, Solenoids, and LEDs. 

This board has a simple plug-and-play JST PH (2mm pitch) input connector for solderless use. Provide power (from 3V up to 30V) and signal (3V to 20V logic level). On the output are two-output terminal blocks, with one block connected to power and the other switched to ground when the signal level is high. In between is an AO3406 N-Channel MOSFET rated for  30Vds, 3.6A peak, and 70mΩ RdsOn plus a 1N4007 flyback diode.

You can also get to all the signal and power pins on a 0.1" breakout header if desired, but we expect most folks will like using it as a solderless MOSFET-buddy. Great for driving motors, inductors, high power LEDs, single-color LED strips, or other loads up with to 1.5 Amps continuous draw, 3 Amp peak. Note that the JST PH connector itself is only rated for 2 Amp continuous.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

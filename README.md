# Mini12

A low-distortion (<0.1% THD) 12W per channel class AB amplifier.

I've also included a LTSpice schematic file if you want to play around with the circuit.


## Schematics

It's a classic class AB amplifier topology. Previously it had a class A pre-amplifier stage but I decided to remove it and let the op-amp handle the voltage and current amplification stages.

![Amplifier](http://i.imgur.com/ooLOsXO.png)

The power supply is very simple since it's supposed to be powered by 6x18650 cells or 2x9V batteries.

![Power Supply](http://i.imgur.com/1NUn6F1.png)

This amplifier also includes a clipping/overload detector:

![Clipping/Overload Detector](http://i.imgur.com/JDpisI1.png)

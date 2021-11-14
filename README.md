# TCA8418-library
Easy and simple C++ library for the TCA8418.

## What is the TCA8418?

The TCA818 from Texas Instruments is an I²C controlled Keypad IC with many advantages, such as:
- Wide operating voltage range from 1.65V-3.6V
- Support of up to 80 buttons / keys
- Integrated deounce time of 50µs
- 18 pins for the key-matrix **which can also be used as GPIOs!**
- I²C speed of up to 1MHz
- Interrupt-Pin for key press (will not be used!)

## What's about this library?

Yes, there already are other libraries for this IC which can also be used in the Arduino IDE.
Still, the are lagging the option to _not_ use the interrupt pin and often seem more complicated than they need to be for simple key-readings.
So here it is.

## Some warnings...

This library is still under heavy developent. It currently lacks an overflow-detection, which means that in this case you have to reset the IC by hand. No worries, it will be fixed in the future.

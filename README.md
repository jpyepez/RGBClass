# RGBClass

Utility class for RGB LEDs.

## Using the class:

Add the header and source files to your project folder and add the `#include "RGB.H"` directive at the top of your main script.

The RGB class can be used as following:

1. Create an RGB instance using the three RGB LED pins:

`RGB rgb(30, 31, 32)`

2. Initialize the RGB LED pins with the `init()` function (and the initial LED values), and then set all three colors with the `set()` function:

`rgb.init(255, 0, 0)`

`rgb.set(255, 255, 255)`

3. Use setter and getter functions for each RGB color:

`rgb.setRed(128)`

`rgb.getGreen()`

`rgb.setBlue(0)`

## Example:
The "RGBLed.ino" file shows a simple example of how to use this class.

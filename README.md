# PCB for the Adafruit Sharp Memory display breakout board

<a href="http://www.adafruit.com/products/1393"><img src="assets/image.jpg?raw=true" width="500px"></a><br />
<a href="https://www.adafruit.com/product/4694"><img src="assets/4694.jpg?raw=true" width="500px"></a>

[The 96x96 resolution SHARP Memory LCD is no longer made, but we have a higher-resolution 168x144 display available in the shop](https://www.adafruit.com/product/3502).

The 1.3" and 2.7" SHARP Memory LCD displays are a cross between an eInk (e-paper) display and an LCD. They have the ultra-low power usage of eInk and the fast-refresh rates of an LCD. This model has a matt silver background, and pixels show up as little mirrors for a silver-reflective display, a really beautiful and unique look. It does not have a backlight, but it is daylight readable. For dark/night reading you may need to illuminate the LCD area with external LEDs.

The display is 3V powered and 3V logic, so we placed it on a fully assembled & tested breakout board with a 3V regulator and level shifting circuitry. The display slots into a ZIF socket on board and we use a piece of double-sided tape to adhere it onto one side. There are four mounting holes so you can easily attach it to a box.

The display is 'write only' which means that it only needs 3 pins to send data. However, the downside of a write-only display is that the entire 96x96 bits (1,152 bytes) must be buffered by the microcontroller driver. On an Arduino Uno/Leonardo that's half the RAM available and so it might not be possible to run this display with other RAM-heavy libraries like SD interfacing.

Check out [this Learn guide](https://learn.adafruit.com/adafruit-sharp-memory-display-breakout/overview) for details on the boards and usage.

[Then download and install our SHARP Memory Display library](https://github.com/adafruit/Adafruit_SHARP_Memory_Display) and the [Adafruit GFX library](https://github.com/adafruit/Adafruit-GFX-Library). Run the example sharpmemtest sketch with the correct data pins to start drawing lines, circles, rectangles, text, etc!

## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Adafruit Industries.  
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution

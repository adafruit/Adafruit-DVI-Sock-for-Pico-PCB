## Adafruit DVI Sock for Pico - Works with HDMI Displays PCB

<a href="http://www.adafruit.com/products/5957"><img src="assets/5957.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit DVI Sock for Pico - Works with HDMI Displays. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5957

### Description

Wouldn't it be cool to display images and graphics directly from your Pico or Pico W to an HDMI monitor or television? We think so! So we designed this DVI Sock with a digital video output (a.k.a DVI) that will work with any HDMI monitor or display. Note it doesn't do audio, just graphics!

We designed this little breakout board after seeing Wren6991's Pico DVI Sock and their cool demos of the Raspberry Pi Pico driving an HDMI display. By using some fun 'abuse' of overclocking and the RP2040's PIO system, a low-cost microcontroller can have great-looking video output. It's great for making demos or just noodling around with digital video generation.

This breakout board has no active components on it. It's just a connector you can plug an HDMI/DVI cable into, and 220 ohm series resistors. Wire it up to the bottom pins of your Pico board, or solder it directly onto the 'end' like a lil PCB sock. The connections that are made:

* GP12 to D0+
* GP13 to D0-
* GP14 to CK+
* GP15 to CK-
* GP16 to D2+
* GP17 to D2-
* GP18 to D1+
* GP19 to D1-
* Pico GND to GND

We also breakout the 5V, GND, Hot-Plug Detect, CEC and Util pins, for more advanced hacking. Note that while technically you're supposed to provide 5V to the DVI port, it isnt convenient to do so on the Sock so it's left disconnected. Since the 5V is used for the I2C EDID EEPROM and we don't care about it, the 'Sock will work just fine without.

If you want a more fully-featured DVI interface for your Pico, check out the DVI PiCowbell or the all-in-one Adafruit RP2040 DVI Feather.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

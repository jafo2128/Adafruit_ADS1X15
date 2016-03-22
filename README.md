Adafruit_ADS1015
================

Driver for TI's ADS1015: 12-bit Differential or Single-Ended ADC with PGA and Comparator
<!-- START COMPATIBILITY TABLE -->

## Compatibility

MCU               | Tested Works | Doesn't Work | Not Tested  | Notes
----------------- | :----------: | :----------: | :---------: | -----
Atmega328 @ 16MHz |      X       |             |            | 
Atmega328 @ 12MHz |      X       |             |            | 
Atmega32u4 @ 16MHz |      X       |             |            | Use SDA/SCL on pins D2 &amp; D3
Atmega32u4 @ 8MHz |      X       |             |            | Use SDA/SCL on pins D2 &amp; D3
ESP8266           |      X       |             |            | SDA/SCL default to pins 4 &amp; 5 but any two pins can be assigned as SDA/SCL using Wire.begin(SDA,SCL)
Atmega2560 @ 16MHz |      X       |             |            | Use SDA/SCL on pins 20 &amp; 21
ATSAM3X8E         |      X       |             |            | Use SDA/SCL on pins 20 &amp; 21
ATSAM21D          |      X       |             |            | 
ATtiny85 @ 16MHz  |      X       |             |            | Use 0 for SDA, 2 for SCL
ATtiny85 @ 8MHz   |      X       |             |            | Use 0 for SDA, 2 for SCL

  * ATmega328 @ 16MHz : Arduino UNO, Adafruit Pro Trinket 5V, Adafruit Metro 328, Adafruit Metro Mini
  * ATmega328 @ 12MHz : Adafruit Pro Trinket 3V
  * ATmega32u4 @ 16MHz : Arduino Leonardo, Arduino Micro, Arduino Yun, Teensy 2.0
  * ATmega32u4 @ 8MHz : Adafruit Flora, Bluefruit Micro
  * ESP8266 : Adafruit Huzzah
  * ATmega2560 @ 16MHz : Arduino Mega
  * ATSAM3X8E : Arduino Due
  * ATSAM21D : Arduino Zero, M0 Pro
  * ATtiny85 @ 16MHz : Adafruit Trinket 5V
  * ATtiny85 @ 8MHz : Adafruit Gemma, Arduino Gemma, Adafruit Trinket 3V

<!-- END COMPATIBILITY TABLE -->




Finally words from us Archivers and Developers.. 

##### Donate

People from time to time wish to donate a little money. Donating won't get you anything special, other than a warm feeling inside, and possibly urge me to produce more freely available material for interesting projects. You can donate via [PayPal](https://www.paypal.com), just click [donate](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3PXVSLXFBS45E) button available below - it will redirect you to the secured PayPal page where you can provide donation amount (there is no minimal value). Any donations are apreciated greatly, and we thank you all in advance for your support along the ways..

[![Donate via PayPal](https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3PXVSLXFBS45E)



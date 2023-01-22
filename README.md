# Uno-Mini-Max
a breadboard sized Uno with many added Features

Vibrino Uno Mini Max: 

is a Powerful, breadboardable Arduino-compatible Uno-style development circuit board with many Extra Features!

Using the ATmega328, I've provided access to all the microprocessor pins, 
added and ICSP to burn the Uno bootloader,

FTDI pins (or use the uUSB connectivity via the CH340E IC to upload sketches),
 
two sets of i2C pin to add an optional sensor module (such as the BME280 Barometer - shown in photos) 

and/or an i2C OLED Display (shown in photos).

An on-board Power Switch makes things easier! Input a DC voltage from +6 to +12 volts via the "RAW" input pins.

Two Voltages Regulators (+5v and +3.3V) supply all necessary power to the circuits.

Optional addons include an RTC Real-Time Clock (with battery backup), uSD Card Reader (for Datalogging) and an EEprom.

Laid out using the EasyEDA software.

NOTE: If an OLED is used, I suggest using the SSD1306Ascii Library to save tons of memory over the Adafruit GFX Library, unless you intend to employ bmp graphics and motion.

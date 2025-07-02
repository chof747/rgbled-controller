# RGB-Led Controller

## Idea

This is a WiFi enabled RGB LED controller with the following features:

- Power in from the main 5V power source and stepping down to 3v3 for the MCU
- Pass through of the power to the led strips
- ESP8266 MCU with boot strap, reset and flash logic
- Programming header for auto-reset and flash enabled programming
- Boot and reset button
- IDC header breaking out I2C, 3v3, GND, FLASH (as additional GPIO) and RESET pin
- LED data out (at level of 5V via level shifter)
- Breakout of not used GPIOs 12-14 plus GND
- Wake up circuit prepared with a solder bridge

## Components

- ESP8266 as an ESP12-F module
- ME6211C33M5G-N (voltage regulator)
- 2n7002 MOSFET (level shifting)
- UMH3N (auto reset circuit)
- Screw terminals for Power in and LED Power + Control out
- IDC 2x3 for I2C breakout
- Std Pin headers for programming header and unused pins breakout
- 0.5A Fuse

## Revision History:

V1.0 
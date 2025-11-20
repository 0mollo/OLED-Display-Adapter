# OLED-Display-Adapter
![image alt]
A compact I2C OLED display adapter board compatible with multiple OLED screen sizes.
This adapter allows simple interfacing between microcontrollers (e.g., ESP8266, ESP32, Arduino) and popular SSD1306-based OLEDs.

## Features
- Communication: I2C
- Supported OLED sizes: 0.49", 0.91", 0.96", 1.3", 1.5"
- Dimensions: 28.30 × 25.60 mm
- Power: 5V output adapter
- Pin header: 1×08 P2.54 mm vertical
- Pinout:
  - **SCL** — D1 / GPIO5
  - **SDA** — D2 / GPIO2

## Schematic
Located in `hardware/schematics/OLED_Display_Piggyback.pdf`

## Arduino Libraries
Ensure you install:
- Adafruit SSD1306
- Adafruit GFX Library

## Example
See `examples/arduino/oled_i2c_example.ino` for initialization and display test.

## Datasheet
OLED display module datasheet is included under `/datasheets/`.

## License
Released under the MIT License.

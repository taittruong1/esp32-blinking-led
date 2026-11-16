# ESP32 Blinking LED

A simple project that blinks an LED on and off every second using an ESP32 board.

## What it does
The ESP32 sets a GPIO pin HIGH (3.3V) for one second, then LOW (0V) for one second, repeating forever. The LED lights up when the pin is HIGH.

## Parts
- ESP32 Dev Module
- 1 LED
- 1 resistor (220 ohm)
- Breadboard
- 2 jumper wires

## Wiring
- GPIO 2 (D2) -> resistor -> LED -> GND

## How to run
1. Open `blinking_led.ino` in the Arduino IDE.
2. Select Tools > Board > ESP32 Dev Module and choose your port.
3. Upload the sketch.

## What I learned
- How a breadboard connects holes in each row
- How current flows in a complete loop from a GPIO pin through the LED to GND
- Why an LED needs a resistor
- The difference between the labels on the board and the GPIO numbers used in code

## Images
https://docs.google.com/document/d/1JjrxrtwKCytsZvnYTaHe1Gj9EO0Yx1IoI51YBKI3Px4/edit?usp=sharing

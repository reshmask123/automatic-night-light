# automatic-night-light
# 💡 Automatic Night Light

An Arduino-based automatic night light that uses an LDR sensor to detect the surrounding light level and automatically controls an LED.

## 🚀 Features

- Automatically turns the LED ON in darkness
- Turns the LED OFF in bright light
- Uses an LDR sensor for light detection
- Simple and low-cost Arduino project
- Designed and simulated using Tinkercad

## 🧰 Components Required

- Arduino Uno R3
- LDR / Photoresistor
- LED
- 220Ω Resistor
- 10kΩ Resistor
- Jumper Wires

## 🔌 Pin Connections

| Component | Arduino Pin |
|---|---|
| LDR | A0 |
| LED | D9 |
| LDR resistor | 10kΩ |
| LED resistor | 220Ω |

### Power Connections

- LDR one leg → 5V
- LDR other leg → A0
- 10kΩ resistor → A0 to GND
- LED long leg → 220Ω resistor → D9
- LED short leg → GND

## 💡 Working Principle

The LDR detects the amount of light around it.

- 🌙 Dark → LED ON
- ☀️ Bright → LED OFF

Arduino continuously reads the LDR value through analog pin A0 and controls the LED accordingly.

## 💻 Software

- Arduino IDE
- Tinkercad Circuits

## 🎯 Project Goal

The goal of this project is to create a simple automatic lighting system that can be used as a basic smart lighting solution.

## 🔮 Future Improvements

- Add multiple LEDs
- Add a PIR motion sensor
- Add adjustable brightness using PWM
- Add IoT-based control

## 👩‍💻 Author

Created as an Arduino and Tinkercad electronics project.

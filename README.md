# Portable, High-Range Temperature Sensor
A small, portable high-range temperature sensor. I made it mostly just to try making something portable/3D printed, but it's also somewhat functional for testing to see if a stove/handle is hot. I didn't know PCB design at the time so it was built with protoboards. The battery % is tracked using a voltage divider and analog reading on the battery voltage. A % is found by assuming Lipo voltage range for 3.2v-4.2v

![Temperature Sensor Photo](./tempsensor.PNG)
^nice

## Features
- -20 to 120 Celsius with a resolution of 0.02 C
- Light weight/ Portable
- Flexable sensor position
- Live Battery % Reading
- LCD Display
- USB-C Fast Charging & +48 hour battery life


## Parts List (rough estimate prices ~ $50 total)
- 3D printed housing (custom made for free @ OU)
- Arduino Nano $5
- 3.7Ah Lipo Battery $7
- TP4056 Lipo Charger/Regulator $1
- SSD1306 LCD Display $5
- MLX90614ESF High Range I2C Temperature Sensor $15
- flexable plastic tube/solder arm $16
- Switch, potentiometer, protoboard, wires, solder $2

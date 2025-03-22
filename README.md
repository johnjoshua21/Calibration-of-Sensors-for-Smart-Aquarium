# Calibration-of-Sensors-for-Smart-Aquarium

This Arduino-based **Smart Aquarium** system monitors the water quality using **pH and temperature sensors** and displays real-time readings on an **LCD screen**. It helps ensure a healthy aquatic environment for your fish.

## Components Required
- **Arduino Board** (Uno/Nano)
- **pH Sensor**
- **DS18B20 Temperature Sensor** (Waterproof)
- **16x2 LCD Display** (I2C or Parallel)
- **I2C Module** (If using I2C LCD)
- **Buzzer** (Optional for alerts)
- **Resistors & Connecting Wires**

### Connections:
- **pH Sensor** → Analog Pin `A0`
- **DS18B20 Temperature Sensor** → Digital Pin `2`
- **LCD Display** → I2C (SDA to `A4`, SCL to `A5`) or parallel connections
- **Buzzer (Optional)** → Digital Pin `3`


## How It Works
1. **Reads water pH** using the pH sensor.
2. **Measures temperature** using the DS18B20 sensor.
3. **Displays values on LCD** in real time.
4. **Triggers a buzzer alert** if pH goes beyond safe limits (6.5 - 8.5).
5. **Prints data to Serial Monitor** for debugging.

## How to Use
1. Assemble the circuit as per the diagram.
2. Upload the provided code to your Arduino board.
3. Place the sensors in the aquarium water.
4. Observe real-time pH and temperature readings on the LCD.
5. If pH levels are unsafe, the buzzer will alert you.

## License
This project is open-source. Feel free to modify and improve it.



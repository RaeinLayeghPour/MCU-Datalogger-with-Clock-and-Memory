# MCU Datalogger with Clock and Memory

A microcontroller-based data logging system featuring a real-time clock (RTC) and external memory (EEPROM/SPI flash) to timestamp and store sensor readings for offline retrieval and analysis.

---

## Features

- Real-time timestamping via DS3231 (I²C RTC module)
- Data storage on external EEPROM or SPI flash memory
- Configurable sampling interval and data format
- Power-efficient design for long-term deployment
- Accessible serial interface for data download/monitoring

---

## Tech Stack & Hardware

- **MCU:** Arduino Uno / ATmega328P
- **RTC:** DS3231 module (I²C)
- **Memory:** External EEPROM or SPI flash (e.g., 24LC256, 25LC512)
- **Language:** Arduino C/C++
- **Interface:** Serial (USB) + I²C/SPI protocols

---

## How It Works

1. On boot, the MCU initializes the RTC and memory.
2. Sensor data (analog/digital) is sampled at configured intervals.
3. Each reading is timestamped using the RTC.
4. Records are stored sequentially in external memory.
5. Data can be retrieved via serial commands (e.g., `dump`, `clear`).

---

## Applications

- Remote environmental monitoring (e.g., temperature, humidity)
- Power data logging (voltage/current)
- Industrial sensing (vibration, pressure)
- Educational electronics and embedded systems projects

---

## 📬 Contact

Reach out if you’d like to collaborate or discuss enhancements:

- 💼 [LinkedIn](https://www.linkedin.com/in/raeinlp)
- ✉️ Email: raeen.layegh2017@gmail.com

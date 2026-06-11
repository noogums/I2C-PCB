i2c-sensor-logger:
  - A 2-layer PCB that logs temperature, humidity, and ambient light over I2C to CSV via USB serial and displays live readings on an SSD1306 OLED. 
    Built around the Raspberry Pi Pico W with TI HDC1080 and OPT3001 sensors.

Hardware:
  - Raspberry Pi Pico W
  - TI HDC1080 — temperature and humidity (±0.2°C, 14-bit)
  - TI OPT3001 — ambient light (23-bit dynamic range)
  - SSD1306 128x64 OLED display
  - MCP1700 3.3V LDO regulator
  - 2-layer FR4 PCB, manufactured by JLCPCB

Measurements: (updated once board comes in)
  - I2C bus waveforms — scope screenshot of SDA/SCL
  - Rise time measured vs calculated
  - Temperature accuracy vs reference thermometer
  - Power consumption on 3.3V rail
  - I2C frequency limit before communication fails

Schematic:
  <img width="1066" height="1028" alt="image" src="https://github.com/user-attachments/assets/7b83f56d-7a9b-4d56-acb7-b5bc86009c7a" />

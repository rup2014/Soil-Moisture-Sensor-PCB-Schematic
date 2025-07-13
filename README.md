# SoilMoistureReaderDesign

This project contains the KiCad schematic and PCB layout for a soil moisture reader built around the ESP32-WROVER module.

## Features

- **ESP32-WROVER Based**: Utilizes the powerful ESP32-WROVER 
- **Programming Header**: A 4x1 header enables convenient programming of the ESP32.
- **OLED Display Support**: A second 4x1 header is provided for connecting an SSD1306 OLED display to show real-time readings.
- **Enable Button**: Used in conjuction with programming header to flash the ESP32.
- **Manual Scan Button**: Includes a button allowing users to manually trigger soil moisture scans.

## Hardware Overview

- **Microcontroller**: ESP32-WROVER
- **Display**: SSD1306 OLED (via header)
- **Programming Interface**: 4x1 header
- **Enable/Reset Button**: Enable Flash/Reset button
- **User Input**: Manual scan button

## Getting Started

1. **Clone the Repository**
   ```
   git clone https://github.com/rup2014/SoilMoistureReaderDesign.git
   ```
2. **Open the KiCad Project**
   - Launch KiCad and open the project files in this repository.
3. **Review Schematics and PCB**
   - Schematics and PCB files are provided for hardware fabrication and modification.

## Usage

- Connect the ESP32-WROVER and SSD1306 OLED as indicated in the schematic.
- Use the programming header for firmware uploads.
- Use the manual scan switch to initiate readings.

## License

This project is open-source. See the LICENSE file for more details.

## Author

- Maintained by [rup2014](https://github.com/rup2014)

---

*For questions or contributions, feel free to open an issue or pull request.*

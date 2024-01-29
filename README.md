# Dual Encoder Module with ATtiny48

![Hardware](https://img.shields.io/badge/Hardware-PCB-red)
![Design](https://img.shields.io/badge/Design-Schematic-blue)
![made-with-eagle](https://img.shields.io/badge/Made%20with-Eagle-blue.svg)
![license](https://img.shields.io/badge/license-MIT-green)

## Overview
This repository is dedicated to the design and implementation of a Dual Encoder Module, featuring two EC12E24204A8 encoders interfaced with an ATtiny48 microcontroller. Designed as an expansion module for the smartboard, it connects via a single smartboard connector, providing precise rotational input control for a wide range of applications.

## Key Features
- **Dual EC12E24204A8 Encoders**: High-quality rotary encoders for accurate and reliable input.
- **ATtiny48 Microcontroller**: Efficiently decodes and manages encoder signals.
- **SPI/UART Communication**: Offers flexible data transfer options to suit different requirements.
- **Smartboard Compatibility**: Easily integrates with smartboard systems through a dedicated connector.
- **Programmable via Connector Signals**: Enables easy programming and configuration.

### Schematic
![Schematic](media/sch.png)
*The schematic diagram provides a detailed view of the circuit design and component connections, essential for understanding the module's functionality and for troubleshooting.*

### Board Design - Top View
![Board Design Top](media/brd_top.png)
*This image shows the top view of the PCB layout, highlighting the placement of components, including the encoders and the ATtiny48 microcontroller.*

### Board Design - Bottom View
![Board Design Bottom](media/brd_bottom.png)
*The bottom view of the PCB layout illustrates the routing of traces and the arrangement of additional components, giving a complete overview of the PCB design.*

### Connector Signals
![Connector Signals](media/CONx1.png)
*This diagram details the signal configuration on the connector used to interface the module with a smartboard, outlining each pin's function and connectivity.*


## Contributions and Feedback
Contributions to this project are welcome. If you have suggestions for improvement or have developed additional features, please fork the repository, make your changes, and submit a pull request. For any questions or issues, please open an issue in the GitHub repository.

## License
This charger project is licensed under the MIT License with the following terms:

- **Permission to Use**: You are free to use, modify, and distribute this charger design in both private and commercial settings.
- **Attribution Requirement**: While not required, attribution to the original author, Adam Łuczak, is appreciated. This can be done through a citation or a link back to this repository.
- **No Warranty**: This design is provided "as is", without warranty of any kind. Use it at your own risk.
- **Liability**: The author is not liable for any damages or losses that may arise from the use of this design.

For the full terms and conditions, please refer to the MIT License documentation.

## Contact
Should you have any inquiries or suggestions regarding this charger project, please don't hesitate to contact Adam Łuczak at adam.luczak@outlook.com.

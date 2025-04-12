Marine Assistant 🐠
Open-source smart aquarium monitoring and control system, built for reef tank automation and fully integrated with Home Assistant.
👉 www.marine-assistant.com

![Marine assistant hardware]([image-url](https://static.wixstatic.com/media/9f83e8_bde41e1b6a6445a0b7062d57c9d55f5f~mv2.png/v1/crop/x_502,y_92,w_940,h_638/fill/w_427,h_290,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/v2%20case%20(v15~recovered)%20PCB.png))

🌟 Features

✅ Monitor water temperature, water level, and leaks

✅ Control 12V and 120V/240V devices (lighting, pumps, fans, etc.)

✅ Support for analog sensors: pH, TDS, EC, ORP

✅ Seamless integration with Home Assistant

✅ Local network operation (no cloud required)

✅ Customizable dashboards and automation logic

🔧 Hardware Requirements
ESP32 or compatible microcontroller
Water temp sensors (DS18B20 recommended)
Optical or float water level sensors
Leak detection sensor
12V relay modules or smart power switches
Analog sensor support via I2C/ADC (for pH, EC, etc.)

Full wiring diagrams and BOM coming soon on the website.

📦 Installation
Clone this repository

bash
Kopieren
Bearbeiten
git clone https://github.com/yourusername/marine-assistant.git
Flash the firmware using PlatformIO or the Arduino IDE

Configure Wi-Fi and MQTT/Home Assistant settings

Connect hardware and start monitoring!

💻 Home Assistant Integration
Marine Assistant communicates with Home Assistant over MQTT or native integrations.
Dashboards, automations, and alerts can be configured easily through the Home Assistant UI.


🤝 Contributing
Pull requests, issue reports, and feature suggestions are welcome! Check out the issues page to get started.

📜 License
This project is licensed under the MIT License. See LICENSE for details.

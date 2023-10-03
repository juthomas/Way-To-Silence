# WAY TO SILENCE

##Goals
- Develop a module, powered by an ESP32, capable of reading audio tracks stored on an SD card and transmitting them through a speaker output. The parameters of these audio tracks, such as volume and balance, should be modifiable via an accessible web interface. Additionally, the control of the tracks and playback settings should be achievable through UDP signals. This interface would allow users to customize their listening experience and adjust the settings to their liking while ensuring fast and efficient communication with the module via UDP. + battery management
##Components
- [I2S Amplifier Module MAX98357A](https://www.lcsc.com/product-detail/Audio-Power-OpAmps_Analog-Devices-Inc-Maxim-Integrated-MAX98357AETE-T_C910544.html) € 0.7886

- [SD Card Connector](https://jlcpcb.com/partdetail/gswitch-GT_TF003_H018502/C5155564) € 0.1553

- [ESP32 4Mb Flash](https://www.lcsc.com/product-detail/WiFi-Modules_Espressif-Systems-ESP32-WROOM-32-N4_C82899.html) € 2.5764

- [ESP32 8Mb Flash](https://www.lcsc.com/product-detail/WiFi-Modules_Espressif-Systems-ESP32-WROOM-32-N8_C529582.html) € 2.9722

- [ESP32 16Mb Flash](https://lcsc.com/product-detail/WiFi-Modules_Espressif-Systems-ESP32-WROOM-32-N16_C529581.html) € 3.3920

- [CP2102](https://www.lcsc.com/product-detail/USB-ICs_SILICON-LABS-CP2102-GMR_C6568.html) € 2.0075

- [CH340C](https://www.lcsc.com/product-detail/USB-ICs_WCH-Jiangsu-Qin-Heng-CH340C_C84681.html) € 0.45

- [BMS SM5308](https://www.lcsc.com/product-detail/Battery-Management-ICs_HICHON-SM5308_C5345582.html) € 0.2758
- [USB C Connector](https://jlcpcb.com/partdetail/Dealon-USB_TYPE_C018/C2927038) $ 0.0479
- [3.3V Regulator](https://www.lcsc.com/product-detail/Linear-Voltage-Regulators-LDO_UMW-Youtai-Semiconductor-Co-Ltd-AMS1117-2-5_C347221.html) € 0.0398

- [Bornier 3.5mm](https://www.lcsc.com/product-detail/Screw-terminal_Ningbo-Xinlaiya-Elec-XY350V-3-5-2P_C784942.html) € 0.1065


## Tools used

- [EasyEDA to KiCad](https://wokwi.com/tools/easyeda2kicad)
- [KiCad](https://www.kicad.org/)
- [LCSC](https://www.lcsc.com/)
- [JCLPCB](https://jlcpcb.com/)
- https://jlcpcb.com/help/article/81-How-to-generate-the-BOM-and-Centroid-file-from-KiCAD
- https://www.youtube.com/watch?v=VejO8rDdhzo
- https://www.pcbway.com/blog/PCB_Design_Tutorial/How_to_add_USB_C_to_your_projects.html
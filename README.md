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
- [3.3V Regulator](https://www.lcsc.com/product-detail/Linear-Voltage-Regulators-LDO_UMW-Youtai-Semiconductor-Co-Ltd-AMS1117-3-3_C347222.html) € 0.0398

- [Bornier 3.5mm](https://www.lcsc.com/product-detail/Screw-terminal_Ningbo-Xinlaiya-Elec-XY350V-3-5-2P_C784942.html) € 0.1065
- [2.2uH Inductance](https://www.lcsc.com/product-detail/Inductors-SMD_KOHERelec-MDA4020-2R2M_C2847469.html) € 0.7154
- [1uH Inductance](https://www.lcsc.com/product-detail/Inductors-SMD_KOHERelec-MDA4020-1R0M_C2847468.html#) € 0.7287
- [Battery Switch](https://jlcpcb.com/partdetail/XkbConnectivity-SS12D10L3/C319013) € 0.8814
- [Reset Button](https://jlcpcb.com/partdetail/Xunpu-TS_1088R02026/C455280) € 0.0448

- [4.7nF Capacitor](https://jlcpcb.com/partdetail/55004-0603B472K500NT/C53987) € 0.0025
- [4.7uF Capacitor](https://jlcpcb.com/partdetail/20375-CL10A475KO8NNNC/C19666) € 0.0095
- [10uF Capacitor](https://jlcpcb.com/partdetail/MurataElectronics-GRM188R60J106ME47D/C77041) € 0.0085	
- [22uF Capacitor](https://jlcpcb.com/partdetail/60514-CL10A226MQ8NRNC/C59461) € 0.0085
- [100nF Capacitor](https://jlcpcb.com/partdetail/Yageo-CC0603KRX7R9BB104/C14663) € 0.0022
- [220pF Capacitor](https://jlcpcb.com/partdetail/1955-CL10B221KB8NNNC/C1603) € 0.0055
- [0Ω Resistor](https://jlcpcb.com/partdetail/21903-0603WAF0000T5E/C21189) € 0.0011
- [100mΩ Resistor](https://jlcpcb.com/partdetail/112253-0603WAF100LT5E/C111027) € 0.0039
- [500mΩ Resistor](https://jlcpcb.com/partdetail/Fojan-FRL0603FR500TS/C2934253) € 0.0031
- [1Ω Resistor](https://jlcpcb.com/partdetail/25955-0603WAJ010JT5E/C25212) € 0.0009
- [1kΩ Resistor](https://jlcpcb.com/partdetail/21904-0603WAF1001T5E/C21190) € 0.0006

- [5.11kΩ Resistor](https://jlcpcb.com/partdetail/419038-TC0350B5111T5E/C425414) € 0.0167
- [10kΩ Resistor](https://jlcpcb.com/partdetail/26547-0603WAF1002T5E/C25804) € 0.0009
- [1MΩ Resistor](https://jlcpcb.com/partdetail/23662-0603WAF1004T5E/C22935) € 0.0011
- [RED LED](https://jlcpcb.com/partdetail/85432-NCD0603R1/C84263) € 0.0078
- [Ferrite Bead](https://jlcpcb.com/partdetail/373749-CBW160808U470T/C394474) € 0.0030
- [Transistor](https://jlcpcb.com/partdetail/Shikues-BC817/C475629) € 0.0150

## Tools used

- [EasyEDA to KiCad](https://wokwi.com/tools/easyeda2kicad)
- [KiCad](https://www.kicad.org/)
- [LCSC](https://www.lcsc.com/)
- [JCLPCB](https://jlcpcb.com/)
- https://jlcpcb.com/help/article/81-How-to-generate-the-BOM-and-Centroid-file-from-KiCAD
- https://www.youtube.com/watch?v=VejO8rDdhzo
- https://www.pcbway.com/blog/PCB_Design_Tutorial/How_to_add_USB_C_to_your_projects.html
# 100Balance2MQTT [![GitHub release](https://img.shields.io/github/release/softwarecrash/100Balance2MQTT?include_prereleases=&sort=semver&color=blue)](https://github.com/softwarecrash/100Balance2MQTT/releases/latest)
Little Program for ESP82XX to get the 100Balance BMS data to web and MQTT

:warning: This firmware requires a license for full functionality. The license is valid for the lifetime of the BMS used. If you set up the Wemos and cable yourself, you can purchase the license at https://all-solutions.store/license (when purchasing the PCBs in the store, it is automatically included). 


# Features:
- captive portal for wifi and MQTT config
- config in webinterface
- switching MOS gates over webinterface, MQTT and via web at /set?loadstate, set SOC over MQTT
- get essential data over webinterface, get all data like cell voltage and more over MQTT
- classic MQTT datapoints or Json string over MQTT
- get Json over web at /livejson?
- firmware update over webinterface
- debug log on Wemos USB (use only if you **don't** supply Wemos from BMS!!!)
- wake the BMS over MQTT or keep it awake (not supported on ESP-01s)
- universal switching output (only with external power supply, not supported on ESP-01s)
- [blink codes](https://github.com/softwarecrash/100Balance2MQTT/wiki/Blink-Codes) for the current state of the ESP (not supported on ESP-01s)
- [Homeassistant Discovery](https://github.com/softwarecrash/100Balance2MQTT/wiki/HomeAssistant-integration)
- [External Temperatur Sensors](https://github.com/softwarecrash/100Balance2MQTT/wiki/Wiring-temperature-sensors)
- with Teapod


**Main screen:**

![image](https://github.com/softwarecrash/100Balance2MQTT/assets/17761850/630b63fa-9093-43e7-a2c0-d4f8648c7ebe)


**Settings:**

![image](https://github.com/softwarecrash/100Balance2MQTT/assets/17761850/f4839109-6d31-4f6b-bfdb-c29350f29c0a)


**Config:**

![image](https://github.com/softwarecrash/100Balance2MQTT/assets/17761850/4b4e9e07-cb65-441c-9ec6-e8e2df84f7c1)


**MQTT Data**

![grafik](https://user-images.githubusercontent.com/44615614/161782578-aabdde4d-4f51-4312-9392-9fdf4d45df24.png)


# How to use:
- flash the bin file to an ESP8266 (recommended Wemos D1 Mini) with [Tasmotizer](https://github.com/tasmota/tasmotizer/releases)
- connect the ESP like the [wiring diagram](https://github.com/softwarecrash/100Balance2MQTT/wiki/Wiring)
- search for the wifi ap "100Balance2MQTT-AP" and connect to it
- surf to 192.168.4.1 and set up your wifi and optional MQTT
- that's it :)

# Completely assembled and tested PCB's

You are welcome to get fully stocked and tested PCB's. These are then already loaded with the lastest firmware. The earnings from the PCBs are used for the further development of existing and new projects.

[![Daly2MQTT-PCB](https://github.com/softwarecrash/100Balance2MQTT/assets/17761850/22e8c226-9603-464c-b1d4-0f7c043b77b4)](https://all-solutions.store)


If interested see [here](https://all-solutions.store)


# Questions? 
[Join the Discord Channel (German / English)](https://discord.gg/7gTJk22JDE)

#
[<img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"/>](https://donate.softwarecrash.de)
# 
[![LICENSE](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

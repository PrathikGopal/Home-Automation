# Home-Assistant-HASSIO Configs:

* My Hardware components are bare minimum and runs at its best.

## Running a Hassio 0.75.1(5th August) version of Home assistant on a Raspberry Pi 3 Model B // 32GB Samsung UHS-1 SD:
* Raspberry Pi Power HUb and Usb with backup Extension board.
* Multiple Amazon Echo Dot// Alexa
* Using Homekit/Homebrigde to get support for Homekit and Siri.
* Using Alexa skills to integrate alexa to HA.
* Using Google Assistant Integrated into HA

## Controllers:
* Home Assistant
* Home Bridge addon on hassio
* iPad for Homebridge
* Magic Mirror for Status and Assistant
* Pi-Hole
* D1 Mini boards with DHT Sensors and other shields publishing to MQTT
* ESP32 for better lighting controls
* ESP8266 NODE MCU
* PN532 Module with NFC and RFID capabilities
* Amazon Echo Dot with HA emulated custom skills via Alexa API.

## Used Components & Resources:
* Sonoff Switches (https://www.itead.cc/sonoff-wifi-wireless-switch.html)
  * With custom firmware (https://github.com/arendst/Sonoff-Tasmota) controlled via MQTT
* Apple Tv3
* Hikvision NVR
* Bruh Multisensor(Supported Features Include)
   * DHT22 temperature sensor
   * DHT22 humidity sensor
   * AM312 PIR motion sensor
   * TEMT600 light sensor
   * RGB led with support for color, flash, fade, and transition
   * Over-the-Air (OTA) upload from the ArduinoIDE
* Matrix MQTT LED - MAX7219 for Messages on key events and sensors
* NFC & RFID Readers for Door Locks & Automations
* Cameras 
   * FFmpeg
   * Rtsp
   * Images
   
## Used HA resources
* iframes - state card - Weather cards data from INSAT
* Custom UI, tiles, Cards, Fans
* Automations - Timers
* Fitbit
* Cloud
* Quote of the Day, logger & History
* Spotify
* IOS notify - Actionable notifications
* Weblinks
* Sensex - Alpha Vantage
* Amazon & Gearbest Item Prices
* Speedtest
* SSL Encryption Checker
* Device Tracker
* Zones
* Darksky api
* Alpha Vantage
* Wunderground API
* Floorplan
  * Roomle for UI Design(you can use others of course)
  * Inkscape
* Best of Themes

## Hassio Addons:
* AppDaemon - Python Apps and HADashboard using AppDaemon 3.x for Home Assistant.
* Bluetooth BCM43xx - Activate Bluetooth for Broadcom 43xx chips
* Caddy Proxy - Caddy Proxy for multiple VHOSTS with ssl
* Grafana - The open platform for beautiful analytics and monitoring.
* InfluxDB - Scalable datastore for metrics, events, and real-time analytics.
* IDE - Advanced IDE for Home Assistant, based on Cloud9 IDE.
* Configurator - Browser-based configuration file editor for Home Assistant.
* Dropbox Sync - Upload your Hass.io backups to Dropbox
* Duck DNS - Free Dynamic DNS (DynDNS or DDNS) service with Let's Encrypt support
* Node-RED - Flow-based programming for the Internet of Things.
* Homebridge - HomeKit support for your Home Assistant instance using Homebridge
* Mosquitto broker - An Open Source MQTT broker
* Samba share - Expose Hass.io folders with SMB/CIFS
* SSH & Web Terminal - SSH Enabler & Web Terminal access to your Home Assistant instance
* TasmoAdmin - Centrally manage all your Sonoff-Tasmota devices.

### Presence-detection:
* IOS app for Hassio
* Nmap
* Owntracks - mqtt and http
* BT Tracking
* Ping
* Zones
* Bayesian Binary Sensor

## Recommended links for more clarity on the setup:
* [Home Assistant](https://home-assistant.io/)
* [SonOff Tasmota FW](https://github.com/arendst/Sonoff-Tasmota)
* [Hikvision rtsp Feed](https://forum.use-ip.co.uk/threads/hikvision-rtsp-stream-urls.890/)
* [Custom_ui - for UI - UX mods](https://github.com/andrey-git/home-assistant-custom-ui)
* [Custom UI Tiles and custom state card](https://github.com/c727/home-assistant-tiles)
* [Homebridge](https://github.com/nfarina/homebridge)
* [Floorplan](https://github.com/pkozul/ha-floorplan)
* [Design Floorplan](https://github.com/pkozul/ha-floorplan/blob/master/own-floorplan-svg-file-tutorial.md)
* [iFrame Statecard](https://github.com/covrig/homeassistant-iframe-card)


## My gui
<img src="https://github.com/PrathikGopal/Home-Automation/blob/master/Images/File1.png" alt="Home" />
<img src="https://github.com/PrathikGopal/Home-Automation/blob/master/Images/File2.png" alt="Weather" />
<img src="https://github.com/PrathikGopal/Home-Automation/blob/master/Images/File3.png" alt="Automations" />
<img src="https://github.com/PrathikGopal/Home-Automation/blob/master/Images/File4.png" alt="System" />
<img src="https://github.com/PrathikGopal/Home-Automation/blob/master/Images/File5.png" alt="Floorplan" />


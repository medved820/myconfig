# to4ko's Home Assistant configuration


First of all - HUGE THANKS to [Alexxit](https://github.com/alexxit), [Omh](https://github.com/omhy/ha), [Vasilchuk](https://github.com/Anonym-tsk), [S_p_i_r_i_t_u_s](https://github.com/Spirituss), [lapatoc](https://github.com/bastshoes), [Vtel](https://github.com/zvldz), [Enzokot](https://github.com/Enzokot), [AVBor](https://github.com/avbor), [Andrew](https://github.com/andrewjswan) for help and support!

**Main Server:** 
  - Ryzen 5 3600 cooled by Noctua NH-U12DX i4 with NM-AM4 kit
  - Asrock Rack x470d4u
  - 2*16gb MICRON (Crucial) DDR4 3200MHz pc-25600 ECC (MTA9ASF2G72AZ-3G2B1)
  - 128Gb Kingston SSD Boot drive
  - Asus Hyper M.2 x16 card v2 (all NVME drives are connected via this card)
  - 512Gb * 2ea ADATA 8200Pro in Raid-1 Root drive
  - 256Gb ADATA 8200Pro as DB drive
  - 256Gb ADATA 8200Pro connected but not used at the moment
  - 3ea WD RED 2Tb (Storage section for critital files) in Software Raid-1 (1 drive is spare)
  - 2Tb Seagate SV35 for pinhole camera records
  - 8TB Toshiba MG06ACA800E as media storage (Torrent heap)
  - Corsair HX1200i Power supply
  - Fractal Design Mini C with be quite Pure Wings 2 120mm PWM fans (3ea)
  - not in use - USR 56k USB Modem
  - Google Coral M.2 Accelerator

**Backup Server:**
  - Asrock 3455-ITX with integrated Celeron j3455
  - 16gb DDR3 RAM
  - 120Gb SSD Crucial BX500

**not in use - MQTT\Zigbee2MQTT Server #1:**
  - Gigabyte Brix Celeron j3455
  - 16gb DDR3 RAM
  - 120Gb SSD Crucial BX500
  - not in use - zzh CC2652R Zigbee Stick

**Test server \ possible next Backup server:**
  - Intel Nuc Celeron N2830
  - 4gb DDR3 RAM
  - 120Gb SSD Crucial BX500

**not in use - Test Server:**
  - Raspberry Pi 3B+
  - 120Gb SSD Crucial BX500

**Network(WAN 500mb\s):**
  - Unifi Dream Machine Pro
  - Unifi Switch 16-150W
  - not in use - Unifi Switch 24
  - Unifi Switch 8-60W (3ea)
  - Unifi Switch Mini
  - Unifi AC-AP-Lite (2ea)
  - Unifi AC AP Pro (3ea)
  - Unifi NanoHD (not in use)
  - Unifi AP AC Mesh with UMA-D

**UPS**
  - Ippon Smart Power Pro 1200
  - Ippon Back Basic 1050
  - Ippon Back Basic 650
  - CyberPower UT650EG 
  
**Surveillance:** 
  - Unifi Protect on Unifi Dream Machine Pro with 3Tb WD Purple
  - Ubiquiti G3 Flex Cameras (6ea)
  - Digma 100
  - Cheap Aliexpress Pinhole cam via Motioneye (motion detection and stream recording)

**Xiaomi\Aqara WiFi Devices:**
  - Xiaomi Gateway v3 (6ea) via [GW3 by AlexxIT](https://github.com/AlexxIT/XiaomiGateway3)
  - Yeelight LED Ceiling Lamp650 (YLXD02YL) (2ea)
  - Yeelight LED Ceiling Lamp Pro White 960mm (YLXD08YL)
  - Yeelight LED Ceiling Light Pro 940mm White (YLXD56YL) 
  - Yeelight LED Ceiling Lamp 480mm White (YLXD05YL)
  - Yeelight LED Light Strip (YLDD01YL)
  - Yeelight LED Light Strip Plus (YLDD04YL) 
  - Yeelight Jiaoyue 260 (YLXD62YI)
  - Xiaomi Yeelight Bedside Lamp 2
  - Yeelight Bedside Lamp D2
  - Xiaomi Philips Smart LED Bulb E27 White (9290012800) (2ea)
  - Xiaomi Philips Zhirui Downlight (9290012799)
  - Yeelight Xiaomi Led Bulb (Color) (YLDP06YL) (2ea)
  - Yeelight Xiaomi Led Tunable Bulb (White) (YLDP05YL) (2ea)
  - not in use - Xiaomi Smart WiFi Power Strip (2ea)
  - Xiaomi Smartmi Humidifier 2
  - Xiaomi Air Purifier 2s
  - Xiaomi Wifi Plugs v2 (4ea)
  - not in use - Xiaomi Wifi Plugs v2 (3ea)
  - not in use - Xiaomi IR controller

**At the moment, all my Zigbee devices are connected via Xiaomi Gateways, except of DIY Geiger meter (it's sitting on SLS Gateway)**

**Xiaomi\Aqara Zigbee Devices:**
  - Aqara Wall Socket (21ea)
  - Aqara Wall Switch Double (4ea)
  - Aqara D1 Wall Switch Tripple (1ea)
  - not in use - Aqara Wall Switch Single (0ea)
  - Aqara Wireless Switch Double (6ea)
  - Aqara\Xiaomi Door Sensor (25ea)
  - Aqara Water Leak Sensor (3ea)
  - Aqara Vibration Sensor (3ea)
  - Aqara\Xiaomi Motion Sensor (14ea)
  - Aqara\Xiaomi Wireless Button (9ea)
  - Aqara\Xiaomi Temp\Himidity sensor (12ea)
  - Xiaomi Plug (26ea)
  - Xiaomi Smoke Detector (1ea)
  - Xiaomi Natural Gas Detector (1ea)
  - Aqara Zigbee Relay (1ea)
  - Xiaomi Light Sensor (2ea)
  - Aqara Opple Wireless Switch (1ea)
  - not in use - Aqara Opple Wireless Switch (4ea)

**ESPHome devices:**
  - Sonoff Basic (2ea)
  - not in use - Sonoff S26 Plugs (3ea)
  - Sonoff Pow R2 (2ea)
  - Sonoff L1
  - Sonoff Mini (3ea)
  - Sonoff 4ch
  - Blitzwolf SHP2 (10ea) and SHP6 (4ea)
  - Blitzwolf LT11
  - not in use - Blitzwolf SS5 dual gang relay
  - MH-Z19B CO2 sensors on Wemos D1 mini (1ea)
  - ESP32 - Domofon (Intercom helper) with Non-Envasive Power meter
  - ESP32 - Node K - Kitchen MH-Z19B, BME280, BHI1750, Water Filter Counters, IR controller
  - ESP32 - Node B - Bathroom Relays (Water vales, Exhaust Fans), Night LED Strip, Dallas sensors on water pipes (Hot and Cold)
  - ESP32 - Node MB - Master Bedroom MH-Z19B, BME280, BHI1750, Dallas sensors (Heating pipe and Outside)
  - ESP32 - Node V - Vova's Room MH-Z19B, BME280, BHI1750, Dallas sensor (Heating pipe)
  - ESP32 - Hood K - Kitchen Hood Fan\Light Control, BME280, Dallas and max6675 
  - ESP32 - BLE Tracker (Nut find 3)
  - ESP32 - BLE Tracker (Xiaomi Scale 2 and Nut find 3)
  - ESP8266 Oven K - Kitchen Oven K-type Thermocouple via max6675
  - ESP32 PZEM HB - Hall Big Breaker Box PZEM-004T
  - Digma IR Remote (3ea)
  - ESP01 (deepsleep on 14500 LiOn batteries) air freshener (Deerma Aerosol Dispenser DEM-PX830)
  - ESP01 Weight Cell
  - D1 Mini LED Bed light
  - D1 Mini S - Sasha's Room MH-Z19B, BME280, BHI1750, WS2812 LES Strip, HA API Watchdog
  - BTF Adressable LED strip Controller (based on esp8265) flashed with ESPHome

**Other Devices:**
  - not in use - DIYRuZ_FreePad v1
  - not in use - LifeControl E27 RGB Lamp
  - not in use - LifeControl Plug (2ea)
  - not in use - Blitzwolf SHP13 Zigbee3.0 Plug (2ea)
  - [SLS Gateway](https://t.me/slsys) by @avenit
  - SLS Gateway v4 by [egony](https://github.com/egony)
  - DIYRuZ_Geiger Sensor via SLS GW
  - Google Home Mini (6ea)
  - not in use - Sonoff Micro via [SonoffLan by AlexxIT](https://github.com/AlexxIT/SonoffLAN) (self powering down)
  - Shelly EM - energy monitoring (comparing to PZEM...not shure which one os better)
  
**Software:**
  - Ubuntu Server 20.04.2 LTS
  - Home Assistant Core Supervised
  - MotionEye (Pinhole camera motion detection)
  - Mosquitto

**DB used:**
  - PostgreSQL
  - InfluxDB

**Add-On's:** 
  - AirCast
  - File Editor
  - Custom deps deployment
  - ESPhome
  - Grafana
  - Hass.io Google Drive Backup
  - IDE
  - Log Viewer
  - Portainer
  - RPC shutdown

**Scripts:**
  - **ipmi_mqtt.sh**  Publishing IPMI, Temp and other system monitoring info to MQTT broker
  - **ha_log_parser.sh**  Backing up HA log to my home directory and splitting it to Error, Warning, Info message type as well as keeping full log. Logs rotated every 5 days.
  - **ya_weather.sh**  Yandex weather fcst ( thanks to [Ivan](https://t.me/configit)  )
  - **root_dev.sh**  Host root device name for monitoring.
  - **gitignore.sh**  bash script to be used after gitigrone file updated
  - **gitupdate.sh**  git upload


[psmqtt](https://github.com/eschava/psmqtt) used to publish host machine status.

# Main page
![Main Page](https://i.ibb.co/BTcVZtt/page1.jpg)
# Security page
![Security page](https://i.ibb.co/vxyRHD3/page2.jpg)
# Devices by room
![Devices by room](https://i.ibb.co/KV7CD01/page3.jpg)
# Sensors by room
![Sensors by room](https://i.ibb.co/vL2M1T1/page4.jpg)
# Utility counters
![Utility counters](https://i.ibb.co/mSYwCjt/page5.jpg)
# Power load
![Power loads](https://i.ibb.co/tsCh1sy/page6.jpg)
# Device trackers
![Device trackers](https://i.ibb.co/XWCCyRY/page7.jpg)
# CCTV
![CCTV](https://i.ibb.co/JnT0sFF/page8.jpg)
# Climate
![Climate](https://i.ibb.co/SvPRtrx/page9.jpg)
# System monitoring
![System monitoring](https://i.ibb.co/sy2KdM0/page10.jpg)
# Main Server Hardware Monitoring
![Main Server Health](https://i.ibb.co/V3rTvPy/page11.jpg)
# Radio
![Radio](https://i.ibb.co/wdNPVvz/page12.jpg)
# Home\Office PCs Telemetry
![Telemetry](https://i.ibb.co/DDnKYWf/page14.jpg)
# Cross Servers Utility Counters
![Utility Counters(cross servers)](https://i.ibb.co/Hx6vrTg/page15.jpg)
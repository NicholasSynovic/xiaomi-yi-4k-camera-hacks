# Xiaomi Yi 4k Camera Hacks

> Softmod hacks to the Xiaomi Yi 4k Action Camera (z16v13...) with firmware 1.10.9

## Table of Contents

- [Xiaomi Yi 4k Camera Hacks](#xiaomi-yi-4k-camera-hacks)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Supported Devices](#supported-devices)
  - [How to Install](#how-to-install)
  - [Hacks From irungentoo](#hacks-from-irungentoo)
  - [Hacks From ddimensia](#hacks-from-ddimensia)

## About

This project wouldn't be possible without the work of [irungentoo](https://github.com/irungentoo/Xiaomi_Yi_4k_Camera/) and [ddimensia](https://github.com/ddimensia/yi_4k_hacks). Please go support their work in whatever way you can.

## Supported Devices

This is a project to combine the work that both of the aforementioned developers have done into one singular repository for the Xiaomi Yi 4k Action Camera (serial number: **z16v13lb622**) on firmware **1.10.9**.

I have no intention of testing this project on other cameras or firmwares. So if you decide to try this out on other firmware, user _beware of unknown bugs_.

## How to Install

1. Download this project as a _.zip_ file
2. Extract it somewhere on your computer
3. Modify any should the file need to be modified. See the [Hacks](#hacks) section for more information
4. On the root of a micro SD card, copy all of the files in the [`hacks`](hacks/) folder to the root of your micro SD card
5. Eject the micro SD card from your computer
6. Turn **off** your Xiaomi Yi 4k Action Camera
7. Plug in the micro SD card
8. Turn **on** your Xiaomi Yi 4k Action Camera
9. The hacks will be applied automatically

## Hacks From irungentoo

- Enable telnet (via [`console_enable.script`](hacks/console_enable.script))
- Enable logging to micro SD card (via [`save_log_enable.script`](hacks/save_log_enable.script))
- Dump camera settings to file on micro SD card (via [`system.pref.download`](hacks/system.pref.download))
- Load camera settings from file on micro SD card (via [`system.pref.upload`](hacks/system.pref.upload.1))

## Hacks From ddimensia

- [`autoexec.ash`](hacks/autoexec.ash) logging (via [`autoexec.ash`](hacks/autoexec.ash))
- Enable USB console (via [`usbConsole.sh`](hacks/scripts/usbConsole.sh))
- Autostart Wifi client (via [`wifiClient.sh`](hacks/scripts/wifiClient.sh), [`wifi_client_enable.script`](hacks/wifi_client_enable.script), and [`wifi_sta.conf`](hacks/wifi_sta.conf))

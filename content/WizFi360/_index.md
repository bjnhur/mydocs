---
title: WizFi360 소개페이지
#date: {{ .Date }}
weight: 1
#chapter: true
#pre: "<b>1. </b>"
pre: "<i class='fas fa-wifi'></i> "
menuTitle: Learn WizFi360
---

## Overview

WizFi360 is a low cost and low-power consumption industrial-grade WiFi module. It is compatible with the IEEE802.11 b/g/n standard and supports SoftAP, Station and SoftAP+Station modes. The serial port baud rate can be up to 2Mbps, which can meet the requirement of various applications.

## Feature

-   WiFi 2.4G, 802.11 b/g/n
-   Support Station / SoftAP / SoftAP+Station operation modes
-   Support “Data pass-through” and “AT command data transfer” mode
-   Support serial AT command configuration
-   Support TCP Server / TCP Client / UDP operating mode
-   Support configuration of operating channel 0 ~ 13
-   Support auto 20MHz / 40MHz bandwidth
-   Support WPA_PSK / WPA2_PSK encryption
-   Serial port baud rate up from 600bps to 2Mbps with 16 common values
-   Support up to 5 TCP / UDP links
-   Obtaining IP address automatically from the DHCP server (Station mode)
-   DHCP service for Wireless LAN clients (AP mode)
-   Support DNS for communication with servers by domain name
-   Support “Keep-Alive” to monitor TCP connection
-   Support “Ping” for monitoring network status
-   Built-in SNTP client for receiving the network time
-   Support built-in unique MAC address and user configurable
-   Support firmware upgrade by UART Download / OTA (via WLAN)
-   Industrial grade (operating temperature range: -40 ° C ~ 85 ° C)
-   CE, FCC, KC, Telec certification

## Details

-   [Documents](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start)
    -   [Datasheet](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#datasheet) : A brief introduction to WizFi360. These documents describe the features, package information and etc.
    -   [AT Instruction set](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#at_instruction_set): It describes the AT Command of WizFi360 and you can confirm the return message by AT command of WizFi360.
    -   [AT command Example](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#at_command_examples): It includes the Basic example using AT command and it is examples of TCP, UDP, SSL use.
    -   [Quick Start Guide](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#quick_start_guide): The examples using the WizFi360-EVB or WizFi360io, it describes the scenarios in order from Hardware setting to an example of AT command usage
    -   [Firmware Update Guide](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#firmware_update_guide): The method of using how to upload firmware
    -   [Application Notes](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#application_notes): The example of Application, TCP/UDP, etc test using the Arduino
    -   [AT Command Comparison Sheet](http://wizwiki.net/wiki/doku.php?id=products:wizfi360:wizfi360ds:start#at_command_comparison_sheet): The AT command comparison with ESP8266 chip
    -   [Ref schematic](https://github.com/Wiznet/Hardware-Files-of-WIZnet/tree/master/07_WizFi_Module/WizFi360-EVB-Shield): Support the schematic of WizFi360-EVB to Gerber, Partlist, Schematic format.
-   For more information visit the [wizfi/Release](https://github.com/wizfi/Release)

## Q & A

-   [WizFi360 Forum](https://forum.wiznet.io/c/wifi-module/wizfi360) - For technical support

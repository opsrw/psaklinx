### Dell PC Lubuntu Linux for Raspbian-RT OS and SDK Embedded Linux Development of ARM SoC in Raspberry Pi; Completed setup, Hardware Dev Board & Software

This is a Dell PC Lubuntu Linux hosted Remote/Cross Development System for Embedded Linux of Broadcom ARM SoC ARM1176JZF-S, Cortex-A7, Cortex-A53 as used in Raspberry Pi. It contains pre-installed apropriated operating system, compilers and IDE's, debuggers, simulators, loaders, executive codes and other useful tools to rapid develop protype and test your embedded software, firmware projects. The kit includes following items:

**(1) PC Computer system:**
# Fast Dell OptiPlex PC Intel CPU Lubuntu Linux 4GB 120GB SSD:
+ Included are Intel Core2Duo 1.86-3.0GHz; 4GB; 120GB SSD; DVD; Lubuntu 64-bit Linux OS installed; Power Cable/Adapter.
- Monitor, Keyboard, Mouse, Wifi card are not included.

**# lubuntu-desktop-amd64:** Lubuntu Linux is a fast and lightweight free operating system for PC computer. The OS and software are pre-installed and configured.
+ User login account is [user1], with password [user123]
+ Root login account is [root] with password [root123]
+ Hostname is [lbuntu]. SSH SCP client can use this instead of IP address
+ SSH SCP client access IP address is [#.#.#.#:22 or lbuntu:22]
+ TightVNC Server password is [vnc123]. For VNC client remote access
+ TightVNC Server is [#.#.#.#:5901 or lbuntu:1]
+ Use command "ifconfig" or "ip a" to find IP address [#.#.#.#]

# Software pre-installed: SSH Server; TightVNC Server; Remmina; Google Chrome; Wine; Sublime Text Editor; Java JDK; XMind; NetBeans IDE; Eclipse IDE; Node-RED; Host GNU C/C++ Compiler x86 64-bits; GDB Server; Python; Python Test Frameworks; Python C/C++ Wrapper

# gcc-linaro-arm-linux-gnueabihf-raspbian: Linaro GNU ARM C C++ Compiler Tools pre-installed in host PC for Cross Development of ARM SoC Raspberry Pi

(2) Raspberry Pi Starter Kit1:
+1 Raspberry Pi 3 B+ ARM SoC Development Board
+1 Circuit Board Protector Clear Acrylic Mouting Plate; Spacers+Nuts+Screws
+1 GPIO Breakout Expansion Kit for Raspberry Pi
+1 Power Adapter DC Out 5V 3A AC In 100-240V US Micro USB for Raspberry Pi
+1 HDMI Male to HDMI Male 24k Premium High Speed Cable 6 ft.
+1 HDMI Male to VGA Female Video Adapter
+1 Ethernet Cable CAT6/5 Straight for Raspberry Pi
+1 USB to TTL Serial Cable 6ft, connect board to PC USB port for debug and log
+1 16GB MicroSDHC Class 10 Flash Memory Card

# 16GB MicroSDHC Class 10 Flash Memory Card pre-installed Raspbian-RT OS and SDK Embedded Linux Development of ARM SoC in Raspberry Pi

# realtimepi-stretch-lite: Raspbian Lite Linux OS with Preempt RT Real-Time patch. Raspbian is a free linux operating system based on Debian optimized for the Raspberry Pi. The OS and software are pre-installed and configured.
+ User login account is [pi], with password [user123]
+ Root login account is [root] with password <root123>
+ Hostname is [rpbianl]. SSH SCP client can use this instead of IP address
+ SSH SCP client access IP address is [#.#.#.#:22 or rpbianl:22]
+ TightVNC Server password is [vnc123]. For VNC client remote access
+ TightVNC Server is [#.#.#.#:5901 or rpbianl:1]
+ Use command "ifconfig" or "ip a" to find IP address [#.#.#.#]

# Software pre-installed: GNU ARM C C++ Compiler; GDB Server; python3; python2.7; Python Test Framework: unittest, unittest.mock, pytest, nose2, Robot Framework; Python Wrapper: CFFI, ctypes, ctypesgen

(3) SDK for ARM SoC Raspberry Pi in C/C++/Python:
# Drivers and Examples: 1-Wire, AD_DA, Audio, CAN, Ethernet, GPIO, I2C, Infrared, ISM_Radio, LCD, LED, Light_bus, PWM, RS-485, SPI, Timers, TP-BUS, UART, USB, Video, WDT

(4) Software Applications Kit SAK in C/C++/Python: AWSIoTEC, AzureIoTAC OuroBone

# AWSIoTEC: SDK for connecting to Amazon Web Services Internet of Things (AWS IoT) from a device using embedded C. <tdl://psofengr__projects.tdl?1612>

# AzureIoTAC: IoT SDK in C for connecting devices to Microsoft Azure IoT services. Written in ANSI C (C99) for portability and broad platform compatibility. tdl://psofengr__projects.tdl?1812

# OuroBone: Embedded Web Server Automation for remote manage, test, and control any embedded device. tdl://psofengr__projects.tdl?1213

(5) Embedded Middleware SDK in C/C++/Python: Argtable; eCLI; zlib; lwIP; jsmn parser; jsonlite; MessagePack; AnyRPC; cJSON; jsonrpc-c; mbedTLS; FatFs; Check; CppUTest; GoogleTest; Unity; LittlevGL; CivetWeb; MIT-Mongoose

# Argtable: A Cross-Platform, Single-File, ANSI C Command-Line Parsing Library that parses GNU-style command-line options.

# eCLI: The embedded Command Line Interpreter, ecli, allows users to bind in a directory of commands and the associated functions to execute those commands. MIT license.

# zlib: is lossless data compression decompression library for use on virtually any computer hardware and operating system. The zlib data format is itself portable across platforms.

# lwIP Lightweight TCP/IP stack: A small TCP/IP implementation for embedded systems. lwIP is used in many commercial products. lwIP is licenced under a BSD-style license.

# jsmn parser: a minimalistic JSON parser in C. It can be easily integrated into resource-limited or embedded projects.

# jsonlite: High performance and low memory footprint C/Objective-C JSON parser for mobile/embedded systems.

# MessagePack: It's like JSON for C and C++. but fast and small.

# AnyRPC: provides a common system to work with a number of different remote procedure call standards for C++. Currently supported RPC standards include: JsonRpc, XmlRpc and MessagePackRpc

# cJSON: Ultralightweight JSON parser in ANSI C. parser, under MIT license.

# jsonrpc-c: C Library for JSON-RPC server. JSON-RPC in C (server only for now). A library for a C program to receive JSON-RPC requests on tcp sockets (no HTTP). Free software, MIT license.

# mbed TLS: makes it trivially easy for developers to include cryptographic and SSL/TLS capabilities in their (embedded) products, facilitating this functionality with a minimal coding footprint.

# FatFs: is a generic FAT/exFAT filesystem module for small embedded systems. It can be incorporated into small microcontrollers with limited resource, such as 8051, PIC, AVR, ARM, Z80, RX and etc.

# Check: A unit testing framework for C. It features a simple interface for defining unit tests, putting little in the way of the developer.

# CppUTest: A C/C++ based unit xUnit test framework for unit testing and for test-driving development (TDD)your code. Portable and simple to use.
# GoogleTest: Google Test is a unit testing library for the C++ programming language, based on the xUnit architecture.

# Unity: Curiously Powerful Unit Testing in C for C. Build with Test-driven Development in mind.

# LittlevGL: Graphics library to create embedded GUI with easy-to-use graphical elements, beautiful visual effects and low memory footprint. Anti-aliasing, opacity, animations using only one frame buffer.

# CivetWeb: Embedded C/C++ web server. Easy to use, powerful, C/C++ embeddable web server with optional CGI, SSL and Lua support. MIT license so you can innovate without restrictions.

# MIT-Mongoose: MIT-licensed Mongoose web server. Provide easy to use, powerful, embeddable web server.

* Guarantee: The source codes are partially tested. Please understand that I cannot give assurances about the suitability for any particular purpose.
* We offer Technical Support and Programming Services via email, phone/text, and remote access. Contact the seller for details.
* If you require any additional configuration or package installation this also can be done - free of charge!
* Download instructions, resources and samples from [https:??github . com?trgtomk?psaklinx] - replace "?" with "/"

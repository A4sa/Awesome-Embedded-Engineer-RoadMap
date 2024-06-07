# Embedded System Engineering Roadmap 



This repository contains a comprehensive roadmap for an Embedded Systems Engineer, covering the key areas of hardware, software, and soft skills. The roadmap is designed to guide aspiring and practicing Embedded Systems Engineers in their professional development.


## Table of Contents

1. [Hardware Roadmap](#hardware-roadmap)
     - [Electronic Basics](#electronic-basics)
     - [Hardware Design](#hardware-design)
     - [Computer Architecture](#computer-architecture)
     - [Microcontroller Programming](#microcontroller-programming)
     - [Interfaces & Protocols](#interfaces--protocols)
2. [Software Roadmap](#software-roadmap)
     -  [Programming Languages](#programming-languages)
     - [Programming Fundamentals](#programming-fundamentals)
     - [Embedded Software Layer](#embedded-software-layer)
     - [MCU Programming](#mcu-programming)
     - [Build Systems & Debugging](#build-systems--debugging)
     - [Embedded Linux](#embedded-linux)
     - [Embedded Operating Systems](#embedded-operating-systems)
3. Soft Skill
     

> **Resource types:**
> - 📘 : Books
> - 🎞️ : Videos
> - 📝 : Write-ups, articles, and blog posts
> - 🔗 : Other links that do not fit into any of the above categories
---
### ✳️ Electronic 
#### 🔵 Electronic Fundamental
#### 🔵 Hardware Design Basic 
#### 🔵 Test Equipment
---
### ✳️ Prototyping Skill
#### 🔵 Bread board
#### 🔵 PCB Design / EMC 
#### 🔵  Soldering / Rework 
---
### ✳️ Computer Architrcture
#### 🔵 RISC

#### 🔵 ARM
- [💎🎞️ ARM Architecture Fundamentals](https://www.youtube.com/watch?v=7LqPJGnBPMM)
- [📘 The Definitive Guide to ARM® Cortex®-M0 and Cortex-M0+ Processors - Joseph Yiu](https://www.oreilly.com/library/view/the-definitive-guide/9780128032787/)
- [📘 The Definitive Guide to ARM® Cortex®-M3 and Cortex®-M4 Processors - Joseph Yiu](https://www.oreilly.com/library/view/the-definitive-guide/9780124080829/)
#### 🔵 Endianess
#### 🔵 SoC
---
### ✳️ Microcontroller
 - Microcontrollers are integrated circuits (ICs) that combine a microprocessor, memory, and input/output (I/O) peripherals on a single chip. They are designed for embedded applications, where they are used to control devices in a variety of industries, including automotive, industrial, consumer electronics, and healthcare.
- Microcontroller families include AVR, PIC, STM32,ESP32, MSP430, MSP432, Raspberry Pi, Beaglebone
#### 🔵 GPIO
#### 🔵 Analog Input
#### 🔵 Analog Output
#### 🔵 Timers / Counter
#### 🔵 Interrupts
#### 🔵 DMA
---
### ✳️ Interfaces & Protocols
Embedded systems often communicate with other devices or external systems via interfaces, protocols. Interfaces provide the physical connections, protocols define data exchange rules. The choice depends on application-specific needs, including bandwidth, distance, security, and power consumption.
#### 🔵 Basic Protocols 
##### 🔶 UART
##### 🔶 I2C
##### 🔶 SPI
##### 🔶 SDIO

- [📝 SDIO Protocol](https://prodigytechno.com/sdio-protocol/)
- [📝 Interface SD CARD with SDIO in STM32](https://controllerstech.com/interface-sd-card-with-sdio-in-stm32/)
- [🔗 SDIO Card Slave Driver - ESP32 - Technical Documents](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/peripherals/sdio_slave.html)

##### 🔶 I3C

- [🎞️ What is I3C®?](https://www.youtube.com/watch?v=g3TBNHec5Ec)
- [🔗 MIPI I3C & MIPI I3C Basic](https://www.mipi.org/specifications/i3c-sensor-specification)
- [📝 I3C Protocol: Understanding and Debug](https://prodigytechno.com/mipi-i3c-protocol-debug/)
- [🎞️ MIPI I3C Basic - The next generation sensor interface enabling low-power IoT applications](https://www.youtube.com/watch?v=xWKxZp_9RFQ)

##### 🔶 1-Wire

- [🎞️ 1-Wire® Technology Overview](https://www.youtube.com/watch?v=CjH-OztKe00)



#### 🔵 Network
#### 🔵 Wireless
#### 🔵 Industrial / Automotive
##### 🔶 Modbus

- [🎞️ What is Modbus and How does it Work?](https://www.youtube.com/watch?v=txi2p5_OjKU)
- [🎞️ How does Modbus Communication Protocol Work?](https://www.youtube.com/watch?v=JBGaInI-TG4)
- [🎞️ MODBUS STM32 (YouTube Playlist)](https://www.youtube.com/playlist?list=PLfIJKC1ud8ggRvaEsMjSEDazoBAnY4MUv)

##### 🔶 RS485

- [🎞️ What is RS485 and How it's used in Industrial Control Systems?](https://www.youtube.com/watch?v=3wgKcUDlHuM)
- [🎞️ What is RS-485?](https://www.youtube.com/watch?v=bt9Px51eP6s)

##### 🔶 EtherCAT

- [🎞️ Microchip University - An Introduction to EtherCAT®, EtherCAT P and the Microchip LAN925x family of Slave Controllers](https://mu.microchip.com/an-introduction-to-ethercat-ethercat-p-and-the-microchip-lan925x-family-of-slave-controllers)

##### 🔶 CoAP & MQTT

- [🎞️ #144 Internet Protocols: CoAP vs MQTT, Network Sniffing, and preparation for IKEA Tradfri Hacking](https://www.youtube.com/watch?v=pfG8uEDZj5g)
- [🎞️ MQTT vs. CoAP | Comparison of IoT Protocols](https://www.youtube.com/watch?v=0CORpVSUQe0)
- [🎞️ Simple ESP32 IoT Sensor Node Tutorial: WiFi Enabled MQTT Sensor Data Node](https://www.youtube.com/watch?v=x5A5S0hoyJ0)
- [🔗 Cellular IoT Fundamentals - Nordic Semiconductor](https://academy.nordicsemi.com/courses/cellular-iot-fundamentals/)

##### 🔶 CAN
 - [🎞️👶 Microchip University - CAN and CAN FD Protocol and Physical Layer Basics](https://mu.microchip.com/understanding-the-can-fd-protocol)
- [📝👶 CAN bus in 2024: Operation, Advantages and Recent Developments](https://www.parlezvoustech.com/en/bus-can-2024-technologie-avantages-evolutions/)
- [🎞️👶 CAN Bus: Serial Communication - How It Works?](https://www.youtube.com/watch?v=JZSCzRT9TTo&t=21s)
- [🎞️👶 CAN Bus: A Beginners Guide Part 1](https://www.youtube.com/watch?v=YBrU_eZM110)
- [🎞️👶 CAN Bus: A Beginners Guide Part 2](https://www.youtube.com/watch?v=z5CVljiLhvc)
- [🎞️💎 Microchip University - Designing and Implementing a CAN FD Network](https://mu.microchip.com/designing-and-implementing-a-can-fd-network)
- [🎞️ Improving my electric longboard with a CAN Bus! What can the CAN Bus do? EB#44](https://www.youtube.com/watch?v=PL0TPdrhMuI)
- [🎞️ CAN Bus, OBD2 & J1939 Explained (YouTube Playlist)](https://www.youtube.com/playlist?list=PLpV68vjf4Xo4vZ_SjJ6tTlomYm-k18vDZ)
- [🎞️ J1939 Explained - A Simple Intro [v2.0 | 2021]](https://www.youtube.com/watch?v=vlqxu9ojbHg)
- [🎞️ Unified Diagnostic Services (UDS) Explained - A Simple Intro [2022]](https://www.youtube.com/watch?v=CV_B8tJgI5E)
---
## Software 
---
### ✳️ Programming language
#### 🔵 C
#### 🔵 C++
#### 🔵 Python
#### 🔵 Assembly
#### 🔵 Rust
---
### ✳️ Programming Fundamental
#### 🔵 Memory Management
#### 🔵 Data Structure and Algothims
#### 🔵 OOPs
---
### ✳️ Embedded Software Layer
#### 🔵Registers
#### 🔵Bit Fields
#### 🔵Memory Maps
---
### ✳️ MCU Programming
#### 🔵Arduino
If you do not have any background in programming the embedded systems, Arduino boards and libraries are the best choice for you to start and learn the basics. Just keep in mind that most of the Arduino libraries are developed for learning purposes and are not optimized to be used in industry.

Additionally, the [Arduino Core](https://github.com/arduino/ArduinoCore-API) takes care of most of the low-level hardware-associated operations that you, as an embedded engineer, should be able to handle yourself or at least have a clear understanding of. If you want to become a professional embedded developer, you should be able to effectively use industry-standard APIs and SDKs provided and approved by microcontroller vendors, such as CMSIS for ARM Cortex-M microcontrollers, STM32Cube for STM32, ESP-IDF for Espressif microcontrollers, etc.

- [🔗 Getting Started with Arduino](https://docs.arduino.cc/learn/starting-guide/getting-started-arduino)
- [🎞️ New Arduino Tutorials (YouTube Playlist)](https://youtube.com/playlist?list=PLGs0VKk2DiYw-L-RibttcvK-WBZm8WLEP)
- [🎞️ Arduino in a commercial product?](https://www.youtube.com/watch?v=c5LzsqeSCAc)
- [🎞️ Arduino Project to Product (YouTube Playlist)](https://www.youtube.com/playlist?list=PLEBQazB0HUyQd6Fsf5NQ75M9llbi1_j_8)
#### 🔵ESP 32
#### 🔵STM32
#### 🔵 Raspberry Pi
#### 🔵 Beaglebone
---
### ✳️ Build System & debugging
#### 🔵 Comiler
 GCC (the GNU Compiler Collection) is a free and open-source compiler system that can compile programs for many different programming languages, including C, 
 C++, Objective-C, Fortran, Ada, and Go. GCC is a popular choice for embedded systems development due to its open source nature, maturity, stability, 
 portability, performance, and large community. On the other hand proprietary compilers like Keil and IAR offer toolchain support, target-specific 
 optimizations, and customer support, which may be preferred for specific projects. 
 
#### 🔵CMake
 CMake and Make are both tools for building software applications. CMake is a meta-build system that generates Makefiles, which are then used by Make to build 
 the software. CMake is more versatile and cross-platform than Make, and it is becoming the more popular choice for modern software development.

#### 🔵 Bash Scripting
 Bash scripting serves as a powerful tool in embedded systems development, enabling developers to automate repetitive tasks, handle complex configurations, and 
 manage the embedded system's environment effectively. Bash scripting is a Linux-specific tool that is not natively integrated into Windows. However, it can be 
 accessed via the Windows Subsystem for Linux (WSL).
#### 🔵GDB
  GDB (GNU Debugger) is a powerful and versatile debugger for source-level and machine-level debugging. It supports a wide range of programming languages, 
  including C, C++, Objective-C, Java, and Rust. GDB is a free and open-source software tool that is widely used by developers and researchers. 
#### 🔵 JTAG
---
### ✳️ Software Development Life Cycle (SDLC) Models

Software Development Life Cycle (SDLC) models provide a structured approach to software development, guiding the process from planning to deployment and maintenance. These models provide a framework for organizing, managing, and executing software projects, ensuring a consistent and efficient development process.

- [📝 What is the software development life cycle?](https://www.coderus.com/the-software-development-lifecycle/)
- [📝 Embedded Product Development Life Cycle: Four Main Steps](https://www.sam-solutions.com/blog/embedded-product-development-life-cycle/)

#### 🔵 Agile / SCRUM

- [📝 Does agile work with embedded software?](https://www.embedded.com/does-agile-work-with-embedded-software/)
- [📝 Scrum for embedded software: Good – but for reasons other than what your manager thinks](https://www.elektrobit.com/trends/scrum-for-embedded-software/)
- [📝 What Is Scrum: A Guide to the Most Popular Agile Framework](https://www.scrumalliance.org/about-scrum)
- [📝 An agile guide to scrum meetings](https://www.atlassian.com/agile/scrum/ceremonies)
- [📝 What is scaled agile framework? (SAFe)](https://www.atlassian.com/agile/agile-at-scale/what-is-safe)
- [🔗 Jira - Issue & Project Tracking Software](https://confluence.atlassian.com/jira)

#### 🔵 V-Model (V-cycle)

- [📝 What is the V model for software development](https://x-engineer.org/v-model-software-development/)
- [📝 V Model In Software Engineering: Ultimate Guideline](https://biplus.com.vn/v-model-in-software-engineering/)

### ✳️ Version Control Systems

Version control systems are essential tools for managing changes to code and other digital assets. They track changes over time, allowing developers to revert to previous versions, collaborate effectively, and identify potential conflicts. Popular version control systems include Git, Mercurial, and Subversion. 

#### 🔵 Git

- [🎞️👶 Git Tutorial for Beginners: Learn Git in 1 Hour](https://www.youtube.com/watch?v=8JJ101D3knE)
- [🎞️ Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git](https://www.youtube.com/watch?v=Uszj_k0DGsg)
---

### ✳️ Embedded Linux 
#### 🔵 Linux Interal & Network
#### 🔵 Kernel Device Driver
---

### ✳️ Embeddedd Operating System
#### 🔵 OS Fundamental
#### 🔵Bare Metal
#### 🔵FreeRTOS

### ✳️ Soft Skills

Similar to other professions, embedded engineers require soft skills that can't be solely obtained from reading or watching videos. These skills are cultivated through interactions and tackling various work obstacles. Improving soft skills is not a one-size-fits-all approach. It will vary based on one's individual traits and requires self-awareness of your strengths and areas for growth. Enhancing these skills takes time and effort.

- [📝 Soft Skills For Embedded Systems Software Developers](https://www.embeddedrelated.com/showarticle/1470.php)
- [📝 10 Skills Every Embedded Engineer Should Have](https://medium.com/@lanceharvieruntime/10-skills-every-embedded-engineer-should-have-dcb867095b91)
---


# Tutorial-Setup-ESP-Matter-SDK-in-Linux
 How to Setup ESP-Matter SDK. Matter Development Environment setup in Ubuntu OS  
  
<img src="/Images/Matter-GH-1.png" height="200" >     <img src="/Images/Matter-GH-2.png" height="200" > 
  
**Matter** is a unified IP-based connectivity protocol that is designed to connect and build open, reliable and secure IoT ecosystems. This new technology and connectivity standard enables communication among a wide range of smart devices. Matter supports IP connectivity over Wi-Fi, Thread and Ethernet.  

**Espressif’s SDK for Matter**  is the official Matter development framework for Espressif’s ESP32 series SoCs.

- It is built on top of the open source Matter SDK, and provides simplified APIs, commonly used peripherals, tools and utilities for security, manufacturing and production accompanied by exhaustive documentation. It includes rich production references, aimed to simplify the development process of Matter products and enable the users to go to production in the shortest possible time.

[Supported Device Types](SUPPORTED_DEVICE_TYPES.md)

## Supported Matter specification versions

| Matter Specification Version |                              Supported Branch                             |
|:----------------------------:|:-------------------------------------------------------------------------:|
|             v1.0             | [release/v1.0](https://github.com/espressif/esp-matter/tree/release/v1.0) |
|             v1.1             | [release/v1.1](https://github.com/espressif/esp-matter/tree/release/v1.1) |
|             v1.2             | [release/v1.2](https://github.com/espressif/esp-matter/tree/release/v1.2) |
|             v1.3             | [release/v1.3](https://github.com/espressif/esp-matter/tree/release/v1.3) |
|     v1.4 (Ongoing effort)    |         [main](https://github.com/espressif/esp-matter/tree/main)         |


## Getting the repositories

For efficient cloning of the ESP-Matter repository, please refer
[Getting the Repositories](https://docs.espressif.com/projects/esp-matter/en/latest/esp32/developing.html#getting-the-repositories)
section in the ESP-Matter Programming Guide.

## Supported ESP-IDF and connectedhomeip versions

- This SDK currently works with commit [9b008bc10d](https://github.com/project-chip/connectedhomeip/tree/9b008bc10d) of connectedhomeip.
- For Matter projects development with this SDK, it is recommended to utilize ESP-IDF [v5.2.3](https://github.com/espressif/esp-idf/tree/v5.2.3).

## Documentation

For a simplified explanation of Matter concepts and internals, please check out the [Espressif's Matter blog series](https://blog.espressif.com/matter-38ccf1d60bcd).

Refer the [Programming Guide](https://docs.espressif.com/projects/esp-matter/en/latest/) for the latest version of the documentation.

**Getting Started:**  
In order to use and get started with Matter on ESP32, you need to install some software packages based on your Operating System. This setup guide helps you on getting everything installed on Linux.

This tutorial is about Setting up Development Environment for Matter in Ubuntu OS. We've discussed..  
- **Matter SDK Programming Guide** - Basic Introduction. 
- **ESP-IDF Setup** - This is a detailed roadmap to walk you through the installation process. We've already covered that in previous Tutorial
- **Matter Setup** - This is a detailed roadmap to walk you through the installation process.  
- **First Steps on ESP-IDF for Matter** - Project Creation
- **Getting Started Projects** - Blink Demo
- **Menu Configuration Tool Demo** using ESP32C3 and C6 Dev Board  

**Software**
- Ubuntu OS 22.04 LTS  
- Matter SDK

**Hardware**
- Espressif ESP32C3 and C6 Development Kit  

------------------------------------------------------------------------------------------------------

📕 **YouTube Video Links**  

- Please note. This tutorial is divided into two parts. In the first part, we will see how to install, set-up, and configure ESP-Matter-SDK, in Ubuntu OS. Then, in next part. The part 2. With the use of ESP-IDF via command-line approach, We will see demo of how to program 2 different ESP32 boards with Matter-Light application firmware. We will program these ESP32 boards as Matter-accessories or end-devices.

▶️  [Tutorial]  Setup Matter Development Environment in Linux - I  - 🔗  https://youtu.be/NFyD5MwxVGw  

▶️  [Tutorial]  Setup Matter Development Environment in Linux - II  - 🔗  

-------------------------------------------------------------------------------------------------------
📒 **Important Links**  
 
🌐 ESP-Matter - 🔗 https://docs.espressif.com/projects/esp-matter/en/latest/esp32/  
🌐 ESP-Matter Repository - 🔗 https://github.com/espressif/esp-matter   
🌐 CHIP Repository - 🔗 https://github.com/project-chip/connectedhomeip/   
🌐 ESP-IDF - 🔗 https://www.espressif.com/en/products/sdks/esp-idf  
🌐 ESP-IDF - 🔗 https://idf.espressif.com/  
📙 ESP-IDF Docs 🔗 https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/index.html  
📘 ESP-IDF Git 🔗 https://github.com/espressif/esp-idf  
📗 ESP-IDF VScode Installation Git Repo - 🔗 https://github.com/espressif/vscode-esp-idf-extension  
📗 ESP-IDF Get Started Examples - 🔗 https://github.com/espressif/esp-idf/tree/master/examples/get-started  


------------------------------------------------------------------------------------------------------

📜 Source Code, Circuit Diagrams and Documentation : 

🌐 GitHub Repository - 🔗 https://github.com/make2explore/Tutorial-Installing-ESP-IDF-on-Ubuntu   
  
🌐 Hackster Blog - 🔗 https://www.hackster.io/make2explore  
  
🌐 Instructable Blog - 🔗 https://www.instructables.com/make2explore  
  

------------------------------------------------------------------------------------------  

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
SparkFun RTK Postcard
========================================

[![SparkFun RTK Postcard](https://cdn.sparkfun.com/r/600-600/assets/parts/2/8/0/3/2/26916-RTK-Postcard-Feature.jpg)](https://www.sparkfun.com/products/26916)

[*SparkFun RTK Postcard (GPS-26916)*](https://www.sparkfun.com/products/26916)


Designed and manufactured in Boulder, CO USA, the [SparkFun RTK Postcard](https://www.sparkfun.com/products/26916) is a compact development board for your high-precision positioning and navigation needs. This board combines the Quectel LG290P GNSS RTK receiver with an Espressif ESP32-PICO-MINI-02 MCU module, running our latest [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware). The ESP32 provides the SparkFun Postcard with WiFi and Bluetooth&trade; connectivity to operate as an NTRIP caster or client. Meanwhile, the 4-pin locking JST-GH connector allows users to transmit or receive RTCMv3 messages for RTK corrections from a local base station.

- The LG290P module is a quad-band, multi-constellation, high-precision, RTK GNSS receiver. The module can simultaneously receive signals from the `L1`, `L2`, `L5`, and `L6`/`E6` frequency bands of the GPS, GLONASS, Galileo, BDS, QZSS, and NavIC GNSS constellations. In addition, the module supports SBAS augmentation systems (WASS, EGNOS, BDSBAS, MSAS, GAGAN, and SDCM), PPP services* (BDS PPP-B2b, QZSS CLAS, MADOCA-PPP, and Galileo HAS), RTCM, and RTK corrections for precision navigation with a fast convergence time and reliable performance. Connect with ease using a variety of interfaces, including UART, SPI*, and I2C*. 

- The ESP32-PICO-MINI-02 is a powerful MCU module with WiFi, Bluetooth&trade;, and BLE connectivity and comes integrated with 8MB SPI flash, 2MB SPI Pseudo static RAM (PSRAM), and a 40 MHz crystal oscillator. The ESP32 microcontroller itself features two CPU cores that can be individually controlled, with an adjustable clock frequency between 80 - 240MHz and a low-power co-processor for minor tasks, such as monitoring peripherals. It supports a range of peripherals including an SD card interface, capacitive touch sensors, ADC, DAC, Two-Wire Automotive Interface (TWAI), Ethernet, high-speed SPI, UART, I2S, I2C, etc.

With the [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware) that comes pre-loaded, users can seamlessly operate the RTK Postcard as a base station or rover. These modes also offer additional functions, based on the available, wireless communication options:

- The RTK Postcard can transmit or receive RTCMv3 messages locally by connecting one of our [SiK Telemetry radios](https://www.sparkfun.com/products/19032).
- Through WiFi or Bluetooth&trade;, the RTK Postcard can also function as an NTRIP caster or client.
- The RTK Postcard can transmit NMEA messages to a [graphical information software (GIS)](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/gis_software_android/) apps on any mobile device when paired as a Bluetooth&trade; device.

In addition to the RTK Postcard, we created the [Portability Shield](https://www.sparkfun.com/products/27510) for the convenience of users. Simply connecting these products, provides a 1.3” OLED display and a five-way button to navigate the configuration settings and display PNT data; a microSD card slot for data logging; and a LiPo battery charger with a fuel gauge to take the RTK Postcard *"on-the-go"*. All of these will operate plug-and-play without the need for new code.

> [!NOTE]
> The [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware) is open-source, so users can obtain, check, and even modify the device's functionality. This allows for easier feature expansion, bug maintenance, and longer device longevity.

> [!NOTE]
> `*`: Feature is still under development

> [!IMPORTANT]
> - Currently, only the UART interface is supported by the LG290P module.
> - Additionally, the corrections for some of the PPP services may not be implemented yet.


Documentation
--------------

* **Hookup Guide (mkdocs)** - The hookup guide for the SparkFun RTK Postcard hosted by GitHub pages.<br>
  [![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)
* [User Manual - RTK Everywhere Firmware](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/) - Documentation for the [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware)
* [SparkFun LG290P GNSS Arduino Library](https://github.com/sparkfun/SparkFun_LG290P_GNSS_Arduino_Library) - An Arduino library for the LG290P GNSS module

*Need to download or print our hookup guide?*

* [Print *(Print to PDF)* from Single-Page View](http://docs.sparkfun.com/SparkFun_RTK_Postcard/print_view)

Repository Contents
-------------------

* **/docs** - Online documentation files
    * assets - Assets files
        * 3d_model - Files for the 3D models
            * 3D CAD Model (.step)
        * board_files - Files for the product design
            * KiCad Design Files (.zip)
            * Schematic (.pdf)
            * Dimension (.pdf)
        * component_documentation - Datasheets for hardware components
        * img/hookup_guide/ - Images for hookup guide documentation
* **[/Hardware](/Hardware/)** - Hardware design files (.brd, .sch)
  * **[/Production](/Production/)** - Production files

Product Variants
----------------

* [GPS-26916](https://www.sparkfun.com/products/26916) - v1.0, Initial Release
* [GPS-26620](https://www.sparkfun.com/products/26916) - SparkFun Quadband GNSS RTK Breakout - LG290P (Qwiic)

Version History
---------------

* [v10](https://github.com/sparkfun/SparkFun_RTK_Postcard/releases/tag/v10) - Initial Release


License Information
-------------------

This product is ***open source***!

Please review the [`LICENSE.md`](./LICENSE.md) file for license information.

If you have any questions or concerns about licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

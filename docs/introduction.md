---
icon: material/book-open-page-variant
---

# Introduction
<div class="grid cards desc" markdown>

-   <a href="https://www.sparkfun.com/products/26916">
	**SparkFun RTK Postcard**<br>
	**SKU:** GPS-26916

	---

	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/0/3/2/26916-RTK-Postcard-Feature.jpg)
	</figure></a>


	<center>
	<article class="video-500px">
	<iframe src="https://www.youtube.com/embed/t00t77OuVi4" title="Product Showcase Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	![QR code to product video](./assets/img/qr_code/product_video.png){ .qr width=100 }
	</article>

	<figure markdown>
	[&nbsp;![QR code to product page](./assets/img/qr_code/product-low.png){ .tinyqr }&nbsp;&nbsp;Purchase from SparkFun :fontawesome-solid-cart-plus:{ .heart }&nbsp;&nbsp;&nbsp;](https://www.sparkfun.com/products/26916){ .md-button .md-button--primary }
	</figure>
	</center>


- Designed and manufactured in Boulder, CO USA, the SparkFun RTK Postcard is a compact development board for your high-precision positioning and navigation needs. This board combines the Quectel LG290P GNSS RTK receiver with an Espressif ESP32-PICO-MINI-02 MCU module, running our latest [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware). The ESP32 provides the SparkFun Postcard with WiFi and Bluetooth&trade; connectivity to operate as an NTRIP caster or client. Meanwhile, the 4-pin locking JST-GH connector allows users to transmit or receive RTCMv3 messages for RTK corrections from a local base station.

	- The LG290P module is a quad-band, multi-constellation, high-precision, RTK GNSS receiver. The module can simultaneously receive signals from the `L1`, `L2`, `L5`, and `L6`/`E6` frequency bands of the GPS, GLONASS, Galileo, BDS, QZSS, and NavIC GNSS constellations. In addition, the module supports SBAS augmentation systems (WASS, EGNOS, BDSBAS, MSAS, GAGAN, and SDCM), PPP services[^2] (BDS PPP-B2b, QZSS CLAS, MADOCA-PPP, and Galileo HAS), RTCM, and RTK corrections for precision navigation with a fast convergence time and reliable performance. Connect with ease using a variety of interfaces, including UART, SPI[^1], and I2C[^1].

	- The ESP32-PICO-MINI-02 is a powerful MCU module with WiFi, Bluetooth&trade;, and BLE connectivity and comes integrated with 8MB SPI flash, 2MB SPI Pseudo static RAM (PSRAM), and a 40 MHz crystal oscillator. The ESP32 microcontroller itself features two CPU cores that can be individually controlled, with an adjustable clock frequency between 80 - 240MHz and a low-power co-processor for minor tasks, such as monitoring peripherals. It supports a range of peripherals including an SD card interface, capacitive touch sensors, ADC, DAC, Two-Wire Automotive Interface (TWAI), Ethernet, high-speed SPI, UART, I2S, I2C, etc.

	With the [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware) that comes pre-loaded, users can seamlessly operate the RTK Postcard as a base station or rover. These modes also offer additional functions, based on the available, wireless communication options:

	- The RTK Postcard can transmit or receive RTCMv3 messages locally by connecting one of our [SiK Telemetry radios](https://www.sparkfun.com/products/19032).
	- Through WiFi or Bluetooth&trade;, the RTK Postcard can also function as an NTRIP caster or client.
	- The RTK Postcard can transmit NMEA messages to a [graphical information software (GIS)](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/gis_software_android/) apps on any mobile device when paired as a Bluetooth&trade; device.

	In addition to the RTK Postcard, we created the [Portability Shield](https://www.sparkfun.com/products/27510) for the convenience of users. Simply connecting these products, provides a 1.3” OLED display and a five-way button to navigate the configuration settings and display PNT data; a microSD card slot for data logging; and a LiPo battery charger with a fuel gauge to take the RTK Postcard *"on-the-go"*. All of these will operate plug-and-play without the need for new code.

	!!! info
		The [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware) is open-source, so users can obtain, check, and even modify the device's functionality. This allows for easier feature expansion, bug maintenance, and longer device longevity.

</div>

!!! warning "Features Under Development"
	- **I^2^C/SPI** - Currently, only the UART interface is supported by the module.
	- **PPP Services** - Corrections for some of the PPP services have not been implemented.

[^1]:
	!!! warning "Feature Under Development"
		**I^2^C/SPI** - Currently, only the UART interface is supported by the module.

[^2]:
	!!! warning "Feature Under Development"
		Corrections for some of the PPP services have not been implemented.


## :fontawesome-solid-list-check:&nbsp;Required Materials
To get started, users will need a few items. Some users may already have a few of these items, feel free to adjust accordingly.

<div class="annotate" markdown>

- Computer and/or mobile device that is compatible with the operation of the [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware)
- [USB 3.1 Cable A to C - 3 Foot](https://www.sparkfun.com/products/14743) - Used to power/interface with the SparkFun RTK Postcard (1)
- [SparkFun RTK Postcard](https://www.sparkfun.com/products/26916)
- GNSS Multi-Band Antenna

</div>

1. If your computer doesn't have a USB-A slot, then choose an appropriate cable or adapter.


<div class="grid cards products" markdown>

-   <a href="https://www.sparkfun.com/products/14743">
	<figure markdown>
	![USB 3.1 Cable A to C - 3 Foot](https://cdn.sparkfun.com/assets/parts/1/2/9/7/2/14743-USB_3.1_Cable_A_to_C_-_3_Foot-01.jpg)
	</figure>

	---

	**USB 3.1 Cable A to C - 3 Foot**<br>
	CAB-14743</a>

-   <a href="https://www.sparkfun.com/products/26916">
	<figure markdown>
	![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/0/3/2/26916-RTK-Postcard-Feature.jpg)
	</figure>

	---

	**SparkFun RTK Postcard**<br>
	GPS-26916</a>

</div>



???+ tip "Recommended Accessories"
	These products are recommended at minimum for users to get started with the [Portability Shield](https://www.sparkfun.com/products/27510) and [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware).

	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/23847">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/1/8/1/23847-Antenna-Feature.jpg)
		</figure>

		---

		**GNSS Multi-Band L1/L2/L5 Helical Antenna (SMA)**<br>
		GPS-23847</a>

	-   <a href="https://www.sparkfun.com/products/27510">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/6/9/2/27510-Portability-Shield-Feature.jpg)
		</figure>

		---

		**SparkFun Portability Shield**<br>
		DEV-27510</a>

	-   <a href="https://www.sparkfun.com/products/116">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/0/6/00116-02-L.jpg)
		</figure>

		---

		**Break Away Headers - Straight**<br>
		PRT-00116</a>

	</div>


	??? note "Soldering Equipment"
		To add headers for the Portability Shield, users will need [soldering equipment](https://www.sparkfun.com/categories/49).


		!!! tip "New to soldering?"
			Check out our [How to Solder: Through-Hole Soldering](https://learn.sparkfun.com/tutorials/5) tutorial for a quick introduction!

			<div class="grid cards" markdown align="center">

			-   <a href="https://learn.sparkfun.com/tutorials/5">
				<figure markdown>
				![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg)
				</figure>

				---

				**How to Solder: Through-Hole Soldering**</a>

			</div>


		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/9325">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/7/3/09325_9161-Solder_Lead_Free_-_100-gram_Spool-01.jpg)
			</figure>

			---

			**Solder Lead Free - 100-gram Spool**<br>
			TOL-09325</a>

		-   <a href="https://www.sparkfun.com/products/24063">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/3/8/5/KIT-24063-PINECIL-Soldering-Iron-Kit-Feature.jpg)
			</figure>

			---

			**PINECIL Soldering Iron Kit**<br>
			KIT-24063</a>

		</div>


	???+ note "*Optional Accessories*"
		These products are optional, based on the utility required by the user.

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/13854">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/1/4/6/1/13854-01.jpg)
			</figure>

			---

			**Lithium Ion Battery - 850mAh**<br>
			PRT-13854</a>

		-   <a href="https://www.sparkfun.com/products/15107">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/3/4/7/0/15107-microSD_Card_-_1GB__Class_4_-01.jpg)
			</figure>

			---

			**microSD Card - 1GB (Class 4)**<br>
			COM-15107</a>

		</div>


???+ note "GNSS Antennas & Accessories"
	For the best performance, we recommend users choose an **active**, multi-band GNSS antenna and utilize a low-loss cable. For additional options, please check out the [GPS Antenna](https://www.sparkfun.com/categories/18) category of our product catalog.

	=== "GNSS Antennas"

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/21801">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/5/9/7/SparkFun_GNSS_SPK6618H_Triband_Antenna_-_2-1.png)
			</figure>

			---

			**GNSS Multi-Band L1/L2/L5 Surveying Antenna - TNC (SPK6618H)**<br>
			GPS-21801</a>

		-   <a href="https://www.sparkfun.com/products/23847">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/1/8/1/23847-Antenna-Feature.jpg)
			</figure>

			---

			**GNSS Multi-Band L1/L2/L5 Helical Antenna (SMA)**<br>
			GPS-23847</a>

		-   <a href="https://www.sparkfun.com/products/23848">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/1/8/2/23848-GNS-Multi-Band-Helical-Antenna_Feature2.jpg)
			</figure>

			---

			**GNSS Multi-Band L1/L2/L5 Helical Antenna - SMA (BT-T009)**<br>
			GPS-23848</a>

		-   <a href="https://www.sparkfun.com/products/17108">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/6/0/7/0/17108-AA.200_____MagmaX2_Active_Multiband_GNSS_Magnetic_Mount_Antenna-01A.jpg)
			</figure>

			---

			**MagmaX2 Active Multiband GNSS Magnetic Mount Antenna - AA.200**<br>
			GPS-17108</a>

		</div>


	=== "Coaxial Cables"

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/21281">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/0/6/5/21281-_CAB-_01.jpg)
			</figure>

			---

			**Interface Cable - SMA Female to SMA Male (10m, RG58)**<br>
			CAB-21281</a>

		-   <a href="https://www.sparkfun.com/products/21740">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/5/7/0/SparkFun_Reinforced_Interface_Cable_-_SMA_Male_to_TNC_Male_-_1.jpg)
			</figure>

			---

			**Reinforced Interface Cable - SMA Male to TNC Male (10m)**<br>
			CAB-21740</a>

		-   <a href="https://www.sparkfun.com/products/21739">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/5/6/9/SparkFun_Reinforced_Interface_Cable_-_SMA_Male_to_TNC_Male_-_4.jpg)
			</figure>

			---

			**Reinforced Interface Cable - SMA Male to TNC Male (300mm)**<br>
			CAB-21739</a>

		</div>


	=== "Mounting Hardware"

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/21257">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/0/2/7/21257-_PRT_M90SD_Magnetic_Stand-_01.jpg)
			</figure>

			---

			**GNSS Magnetic Antenna Mount - 5/8" 11-TPI**<br>
			PRT-21257</a>

		-   <a href="https://www.sparkfun.com/products/19576">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/9/2/4/1/19576-SMA_antenna_Mag_Mount-_01.jpg)
			</figure>

			---

			**Magnetic Mount SMA - 2m**<br>
			GPS-19576</a>

		-   <a href="https://www.sparkfun.com/products/17519">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/6/5/9/3/17519-GPS_Antenna_Ground_Plate-01.jpg)
			</figure>

			---

			**GPS Antenna Ground Plate**<br>
			GPS-17519</a>

		-   <a href="https://www.sparkfun.com/products/22197">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/2/0/9/7/22197-_01.jpg)
			</figure>

			---

			**GNSS Antenna Mounting Hardware Kit**<br>
			KIT-22197</a>

		-   <a href="https://www.sparkfun.com/products/17546">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/6/4/2/7/17546-1_4in._to_5_8in._Adapter_for_5_8in._Thread-01.jpg)
			</figure>

			---

			**Antenna Thread Adapter - 1/4in. to 5/8in.**<br>
			PRT-17546</a>

		-   <a href="https://www.sparkfun.com/products/25795">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/6/4/8/2/25795-Telescopic-Surveying-Pole-Front.jpg)
			</figure>

			---

			**Telescopic Surveying Pole**<br>
			GPS-25795</a>

		</div>



??? note "Serial Transceivers, UART Adapters, and USB Cables"
	To configure the UART ports that are broken out on the board, users will need a [UART adapter](https://www.sparkfun.com/categories/349). Once configured, the UART ports can utilize one of our RF transceivers to send/receive RTCM messages.

	=== "Transceivers"

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/19032">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/8/6/3/4/19032-SiK_Telemetry_Radio_V3_-_915MHz__100mW-01.jpg)
			</figure>

			---

			**SiK Telemetry Radio V3 - 915MHz, 100mW**<br>
			WRL-19032</a>

		-   <a href="https://www.sparkfun.com/products/20029">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/9/7/9/0/SparkFun_LoRaSerial_Enclosed_-_20029-1.jpg)
			</figure>

			---

			**SparkFun LoRaSerial Kit - 915MHz (Enclosed)**<br>
			WRL-20029</a>

		-   <a href="https://www.sparkfun.com/products/17239">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/6/2/2/2/17239-GHR-04V-S_to_GHR-06V-S_Cable_-_150mm-01.jpg)
			</figure>

			---

			**JST-GHR-04V to JST-GHR-06V Cable - 1.25mm pitch**<br>
			CAB-17239</a>

		-   <a href="https://www.sparkfun.com/products/17854">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/7/0/3/4/17854-GHR-04V-S_to_GHR-06V-S_Cable_-_50mm-01.jpg)
			</figure>

			---

			**GHR-04V-S to GHR-06V-S Cable - 100mm**<br>
			CAB-17854</a>

		-   <a href="https://www.sparkfun.com/products/17240">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/6/2/2/3/17240-Breadboard_to_GHR-04V-S_Cable_-_150mm-01.jpg)
			</figure>

			---

			**Breadboard to JST-GHR-04V Cable - 4-Pin x 1.25mm Pitch**<br>
			CAB-17240</a>

		</div>


	=== "UART Adapters"

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/15096">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/3/4/5/2/15096-SparkFun_Serial_Basic_Breakout_-_CH340C_and_USB-C-01.jpg)
			</figure>

			---

			**SparkFun Serial Basic Breakout - CH340C and USB-C**<br>
			DEV-15096</a>

		-   <a href="https://www.sparkfun.com/products/14050">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/1/8/8/8/14050-01.jpg)
			</figure>

			---

			**SparkFun Serial Basic Breakout - CH340G**<br>
			DEV-14050</a>

		-   <a href="https://www.sparkfun.com/products/18289">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/7/6/1/9/18289-SparkFun_FTDI_Starter_Kit_-_3.3V-01.jpg)
			</figure>

			---

			**SparkFun FTDI Starter Kit - 3.3V**<br>
			KIT-18289</a>

		</div>


	=== "USB Cables"

		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/24060">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/4/3/8/2/CAB-24060-USBC-to-USBC-Silicone-Power-Charging-Cable-Feature.jpg)
			</figure>

			---

			**USB-C to USB-C Silicone Power Charging Cable - 3m**<br>
			CAB-24060</a>

		-   <a href="https://www.sparkfun.com/products/14743">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/2/9/7/2/14743-USB_3.1_Cable_A_to_C_-_3_Foot-01.jpg)
			</figure>

			---

			**USB 3.1 Cable A to C - 3 Foot**<br>
			CAB-14743</a>

		-   <a href="https://www.sparkfun.com/products/21271">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/0/4/9/21271-_CAB-_01.jpg)
			</figure>

			---

			**SparkFun 4-in-1 Multi-USB Cable - USB-C Host**<br>
			CAB-21271</a>

		-   <a href="https://www.sparkfun.com/products/21272">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/1/0/5/0/21272-_CAB-_01.jpg)
			</figure>

			---

			**SparkFun 4-in-1 Multi-USB Cable - USB-A Host**<br>
			CAB-21272</a>

		</div>



???+ note "Shields, Headers, and Wiring"
	To add headers or wiring, users will need [soldering equipment](https://www.sparkfun.com/categories/49) and [headers](https://www.sparkfun.com/categories/381)/[wires](https://www.sparkfun.com/catalogsearch/result/?q=hook-up+wire).


	!!! tip "New to soldering?"
		Check out our [How to Solder: Through-Hole Soldering](https://learn.sparkfun.com/tutorials/5) tutorial for a quick introduction!

		<div class="grid cards" markdown align="center">

		-   <a href="https://learn.sparkfun.com/tutorials/5">
			<figure markdown>
			![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg)
			</figure>

			---

			**How to Solder: Through-Hole Soldering**</a>

		</div>


	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/9325">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/7/3/09325_9161-Solder_Lead_Free_-_100-gram_Spool-01.jpg)
		</figure>

		---

		**Solder Lead Free - 100-gram Spool**<br>
		TOL-09325</a>

	-   <a href="https://www.sparkfun.com/products/27147">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/3/0/0/TOL-27147-Ifixit-Portable-Soldering-Station-Feature2.jpg)
		</figure>

		---

		**iFixit FixHub - Power Series Portable Soldering Station**<br>
		TOL-27147</a>

	-   <a href="https://www.sparkfun.com/products/27510">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/6/9/2/27510-Portability-Shield-Feature.jpg)
		</figure>

		---

		**SparkFun Portability Shield**<br>
		DEV-27510</a>

	-   <a href="https://www.sparkfun.com/products/116">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/0/6/00116-02-L.jpg)
		</figure>

		---

		**Break Away Headers - Straight**<br>
		PRT-00116</a>

	-   <a href="https://www.sparkfun.com/products/11896">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/r/455-455/assets/parts/8/1/1/8/11896-01.jpg)
		</figure>

		---

		**Header - 10-pin Female (PTH, 0.1")**<br>
		PRT-11896</a>

	-   <a href="https://www.sparkfun.com/products/11375">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/7/1/2/0/11375-Hook-Up_Wire_-_Assortment__Solid_Core__22_AWG_-01.jpg)
		</figure>

		---

		**Hook-Up Wire - Assortment (Stranded, 22 AWG)**<br>
		PRT-11375</a>

	</div>


	??? note "Batteries"
		When using the [Portability Shield](https://www.sparkfun.com/products/27510), users can attach a single-cell LiPo [battery](https://www.sparkfun.com/categories/54) to turn the boards into a mobile device.

		???+ tip "Minimum Requirements"
			=== "Battery Voltage"
				While users could probably discharge their LiPo batteries down to the maximum threshold of the battery's UVLO at **2.8V**, the LG290P GNSS receiver and ESP32 MCU will discontinue operating, long 	before that can occur. We have found that the LG290P will begin to brown-out around **3.05-3.15V** and the ESP32 will stop operating around **2.85-2.90V**.

				Therefore, users also won't be able to power this device with two 1.5V alkaline batteries *(in series)*. They will require a minimum of three batteries to maintain an operational voltage, above **3.	15V**.

			=== "Battery Capacity"
				The discharge rate of most single-cell batteries is 1C, unless specified otherwise.

				!!! example
					That means that the maximum current that can be expected from a battery is equal its capacity/hr. For instance, a 400mAh battery can be expected to handle a current draw of 400mA, at maximum.


		<div class="grid cards" markdown>

		-   <a href="https://www.sparkfun.com/products/13851">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/1/4/5/8/13857-01.jpg)
			</figure>

			---

			**Lithium Ion Battery - 400mAh**<br>
			PRT-13851</a>

		-   <a href="https://www.sparkfun.com/products/13854">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/1/4/6/1/13854-01.jpg)
			</figure>

			---

			**Lithium Ion Battery - 850mAh**<br>
			PRT-13854</a>

		-   <a href="https://www.sparkfun.com/products/18286">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/7/6/0/6/17748-Lithium_Ion_Battery_-_1250_mAh__IEC62133_certified_-01.jpg)
			</figure>

			---

			**Lithium Ion Battery - 1250mAh (IEC62133 Certified)**<br>
			PRT-18286</a>

		-   <a href="https://www.sparkfun.com/products/26059">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/6/8/8/0/PRT-26059-Lithium-Ion-Battery-Feature.jpg)
			</figure>

			---

			**Lithium Ion Battery - 1500mAh (IEC62133 Certified)**<br>
			PRT-26059</a>

		-   <a href="https://www.sparkfun.com/products/13855">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/1/4/6/2/13855-01.jpg)
			</figure>

			---

			**Lithium Ion Battery - 2Ah**<br>
			PRT-13855</a>

		-   <a href="https://www.sparkfun.com/products/13856">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/1/4/6/3/13856-01.jpg)
			</figure>

			---

			**Lithium Ion Battery - 6Ah**<br>
			PRT-13856</a>

		-   <a href="https://www.sparkfun.com/products/18769">
			<figure markdown>
			![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/8/3/2/5/14188-01.jpg)
			</figure>

			---

			**Battery Holder 3xAA with Cover and Switch - JST Connector**<br>
			PRT-18769</a>

		</div>



??? note "Qwiic Devices and Cables"
	Our Qwiic connect system is a simple solution for daisy chaining I^2^C devices without the hassle of soldering or checking wire connections. Check out other [Qwiic devices](https://www.sparkfun.com/categories/399) from our catalog.

	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/23453">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/3/7/6/0/23453-Qwiic-OLED-Feature-WithDisplay.jpg)
		</figure>

		---

		**SparkFun Qwiic OLED - (1.3in., 128x64)**<br>
		LCD-23453</a>

	-   <a href="https://www.sparkfun.com/products/27576">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/)
		</figure>

		---

		**SparkFun Qwiic Navigation Switch**<br>
		PRT-27576</a>

	-   <a href="https://www.sparkfun.com/products/26851">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/7/9/6/9/26851-Qwiic-Directional-Pad-Feature.jpg)
		</figure>

		---

		**SparkFun Qwiic Directional Pad**<br>
		PRT-26851</a>

	-   <a href="https://www.sparkfun.com/products/15081">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/3/4/3/1/15081-_01.jpg)
		</figure>

		---

		**SparkFun Qwiic Cable Kit**<br>
		KIT-15081</a>

	-   <a href="https://www.sparkfun.com/products/15109">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/3/4/7/5/15109-Qwiic_Cable_-_Grove_Adapter__150mm_-01.jpg)
		</figure>

		---

		**Qwiic Cable - Grove Adapter (100mm)**<br>
		PRT-15109</a>

	-   <a href="https://www.sparkfun.com/products/19833">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/r/455-455/assets/parts/1/9/5/4/5/19833_DiagEdited.jpg)
		</figure>

		---

		**SparkFun Micro Pressure Sensor - BMP384 (Qwiic)**<br>
		SEN-19833</a>

	-   <a href="https://www.sparkfun.com/products/16842">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/r/455-455/assets/parts/1/5/7/6/7/16842-SparkFun_Qwiic_Button_-_Green_LED-01.jpg)
		</figure>

		---

		**SparkFun Qwiic Button - Green LED**<br>
		BOB-16842</a>

	</div>

	!!! tip "What is Qwiic?"

		<div class="grid" markdown>

		<div markdown>

		<!-- Qwiic Banner -->
		<center>
		[![Qwiic Logo - light theme](./assets/img/qwiic/qwiic_logo-light.png#only-light){ width=400 }](https://www.sparkfun.com/qwiic)
		[![Qwiic Logo - dark theme](./assets/img/qwiic/qwiic_logo-dark.png#only-dark){ width=400 }](https://www.sparkfun.com/qwiic)
		</center>

		---

		The [Qwiic connect system](https://www.sparkfun.com/qwiic) is a solderless, polarized connection system that allows users to seamlessly daisy chain I^2^C boards together. Play the video, to learn more about the Qwiic connect system or click on the banner above to learn more about [Qwiic products](https://www.sparkfun.com/qwiic).

		</div>

		<div style="max-height=400px;" markdown>

		<center>
		<div class="video-500px">
		<iframe src="https://www.youtube.com/embed/x0RDEHqFIF8" title="SparkFun's Qwiic Connect System" frameborder="0" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

		![QR code to instructional video](./assets/img/qr_code/qwiic_video.png){ .qr width=100 }
		</div>
		</center>

		</div>

		</div>


		!!! info "Features of the Qwiic System"

			=== "No Soldering"

				![no soldering - light theme](./assets/img/qwiic/no_soldering-light.png#only-light){ align="left" width="90" }
				![no soldering - dark theme](./assets/img/qwiic/no_soldering-dark.png#only-dark){ align="left" width="90" }

				Qwiic cables (4-pin JST) plug easily from development boards to sensors, shields, accessory boards and more, making easy work of setting up a new prototype.

			=== "Polarized Connector"

				![polarized connector - light theme](./assets/img/qwiic/polarized_connector-light.png#only-light){ align="left" width="90" }
				![polarized connector - dark theme](./assets/img/qwiic/polarized_connector-dark.png#only-dark){ align="left" width="90" }

				There's no need to worry about accidentally swapping the `SDA` and `SCL` wires on your breadboard. The Qwiic connector is polarized so you know you’ll have it wired correctly every time.

				The part numbers for the PCB connector is `SM04B-SRSS` ([Datasheet](https://cdn.sparkfun.com/assets/parts/1/2/2/8/9/Qwiic_Connector_Datasheet.pdf)) and the mating connector on the cables is `SHR04V-S-B`; or an equivalent *1mm pitch, 4-pin JST connection*.

			=== "Daisy Chain-able"

				![daisy chainable - light theme](./assets/img/qwiic/daisy_chainable-light.png#only-light){ align="left" width="90" }
				![daisy chainable - dark theme](./assets/img/qwiic/daisy_chainable-dark.png#only-dark){ align="left" width="90" }

				It’s time to leverage the power of the I^2^C bus! Most Qwiic boards will have two or more connectors on them, allowing multiple devices to be connected.



??? note "Jumper Modification"
	To modify the [jumpers](../hardware_overview/#jumpers), users will need [soldering equipment](https://www.sparkfun.com/categories/49) and/or a [hobby knife](https://www.sparkfun.com/categories/379).


	!!! tip "New to jumper pads?"
		Check out our [Jumper Pads and PCB Traces Tutorial](https://learn.sparkfun.com/tutorials/664) for a quick introduction!

		<div class="grid cards" markdown align="center">

		-   <a href="https://learn.sparkfun.com/tutorials/664">
			<figure markdown>
			![Tutorial thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg)
			</figure>

			---

			**How to Work with Jumper Pads and PCB Traces**</a>

		</div>


	<div class="grid cards" markdown>

	-   <a href="https://www.sparkfun.com/products/27147">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/3/0/0/TOL-27147-Ifixit-Portable-Soldering-Station-Feature2.jpg)
		</figure>

		---

		**iFixit FixHub - Power Series Portable Soldering Station**<br>
		TOL-27147</a>

	-   <a href="https://www.sparkfun.com/products/9200">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/6/4/6/09200-Hobby_Knife-01.jpg)
		</figure>

		---

		**Hobby Knife**<br>
		TOL-09200</a>

	-   <a href="https://www.sparkfun.com/products/14579">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/1/2/7/2/5/14579-Chip_Quik_No-Clean_Flux_Pen_-_10mL-01.jpg)
		</figure>

		---

		**Chip Quik No-Clean Flux Pen - 10mL**<br>
		TOL-14579</a>

	-   <a href="https://www.sparkfun.com/products/9327">
		<figure markdown>
		![Product Thumbnail](https://cdn.sparkfun.com/assets/parts/2/8/7/5/09327-Solder_Wick__2_5ft._-_Generic-01.jpg)
		</figure>

		---

		**Solder Wick #2 5ft. - Generic**<br>
		TOL-09327</a>

	</div>



## :material-bookshelf:&nbsp;Suggested Reading

As a more sophisticated product, we will skip over the more fundamental tutorials (i.e. [**Ohm's Law**](https://learn.sparkfun.com/tutorials/voltage-current-resistance-and-ohms-law) and [**What is Electricity?**](https://learn.sparkfun.com/tutorials/what-is-electricity)). However, below are a few tutorials that may help users familiarize themselves with various aspects of the board.

!!! tip
	Check out the [www.gps.gov](https://www.gps.gov/) website to learn more about the U.S.-owned [Global Positioning System (GPS)](https://www.gps.gov/systems/gps/) and the [Global Navigation Satellite Systems (GNSS) of other countries](https://www.gps.gov/systems/gnss/).


<div class="grid cards" markdown align="center">

-   <a href="https://learn.sparkfun.com/tutorials/9">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/parts/5/9/7/4/10890-01.jpg)
	</figure>

	---

	**GPS Basics**</a>

-   <a href="https://learn.sparkfun.com/tutorials/813">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/178-100/assets/learn_tutorials/8/1/3/Location-Wandering-GPS-combined.jpg)
	</figure>

	---

	**What is GPS RTK?**</a>

-   <a href="https://docs.sparkfun.com/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/">
	<figure markdown>
	![Tutorial Thumbnail](https://docs.sparkfun.com/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/assets/img/thumbnail.jpg)
	</figure>

	---

	**Quadband GNSS RTK Breakout - LG290P (Qwiic) Hookup Guide**</a>

-   <a href="https://docs.sparkfun.com/SparkFun_Portability_Shield/">
	<figure markdown>
	![Tutorial Thumbnail](https://docs.sparkfun.com/SparkFun_Portability_Shield/assets/img/thumbnail.jpg)
	</figure>

	---

	**Portability Shield Hookup Guide**</a>

-   <a href="https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware">
	<figure markdown>
	![Tutorial Thumbnail](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/img/thumbnail.jpg)
	</figure>

	---

	**SparkFun RTK Everywhere Product Manual**</a>

-   <a href="https://learn.sparkfun.com/tutorials/62">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/2/Input_Output_Logic_Level_Tolerances_tutorial_tile.png)
	</figure>

	---

	**Logic Levels**</a>

-   <a href="https://learn.sparkfun.com/tutorials/8">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/7/d/f/9/9/50d24be7ce395f1f6c000000.jpg)
	</figure>

	---

	**Serial Communication**</a>

-   <a href="https://learn.sparkfun.com/tutorials/112">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/1/2/thumb.jpg)
	</figure>

	---

	**Serial Terminal Basics**</a>

-   <a href="https://learn.sparkfun.com/tutorials/82">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/8/2/I2C-Block-Diagram.jpg)
	</figure>

	---

	**I2C**</a>

-   <a href="https://learn.sparkfun.com/tutorials/16">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/6/spiThumb_Updated.jpg)
	</figure>

	---

	**SPI**</a>

-   <a href="https://learn.sparkfun.com/tutorials/36">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/3/6/Bench_Power_Supply.jpg)
	</figure>

	---

	**How to Power a Project**</a>

-   <a href="https://learn.sparkfun.com/tutorials/5">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/e/3/9/9/4/51d9fbe1ce395f7a2a000000.jpg)
	</figure>

	---

	**How to Solder: Through-Hole Soldering**</a>

-   <a href="https://learn.sparkfun.com/tutorials/664">
	<figure markdown>
	![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/6/6/4/PCB_TraceCutLumenati.jpg)
	</figure>

	---

	**How to Work with Jumper Pads and PCB Traces**</a>

</div>

??? info "Related Blog Posts"
	Additionally, users may be interested in these blog post articles on GNSS technologies:

	<div class="grid cards" markdown align="center">

	-   <a href="https://www.sparkfun.com/news/4276">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/home_page_posts/4/2/7/6/GPSvGNSSHomepageImage4.png)
		</figure>

		---

		**GPS vs GNSS**</a>

	-   <a href="https://www.sparkfun.com/news/7138">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/home_page_posts/7/1/3/8/SparkFun_RTK_Facet_-_Surveying_Monopod.jpg)
		</figure>

		---

		**What is Correction Data?**</a>

	-   <a href="https://www.sparkfun.com/news/7533">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/home_page_posts/7/5/3/3/rtk-blog-thumb.png)
		</figure>

		---

		**Real-Time Kinematics Explained**</a>

	-   <a href="https://www.sparkfun.com/news/7401">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/home_page_posts/7/4/0/1/Screen_Shot_2023-06-26_at_8.30.22_PM.png)
		</figure>

		---

		**New Video: Unlocking High-Precision RTK Positioning**</a>

	-   <a href="https://www.sparkfun.com/news/9514">
		<figure markdown>
		![Tutorial Thumbnail](https://cdn.sparkfun.com/c/264-148/assets/home_page_posts/9/5/1/4/DIY-Surveying-Blog__1_.jpg)
		</figure>

		---

		**DIY RTK Surveying**</a>

	</div>

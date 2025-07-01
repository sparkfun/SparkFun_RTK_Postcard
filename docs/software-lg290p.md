---
icon: fontawesome/solid/satellite
---

## CH342 USB Driver
The USB drivers for the CH342 USB-to-Serial converter can be downloaded from the [manufacturer's website](https://www.wch-ic.com/search?q=CH342&t=downloads).

<div class="grid cards" align="center" markdown>

-   :material-microsoft-windows: **Windows**

	---

	[:octicons-download-16:{ .heart } Download Page for `CH343SER.EXE`](https://www.wch-ic.com/downloads/CH343SER_EXE.html){ .md-button .md-button--primary target="blank" }


-   :material-apple: **MacOS**

	---

	[:octicons-download-16:{ .heart } Download Page for `CH341SER_MAC.ZIP`](https://www.wch-ic.com/downloads/CH34XSER_MAC_ZIP.html){ .md-button .md-button--primary target="blank" }


</div>


!!! info "Linux"
	A USB driver is not required for Linux based operating systems.



## GNSS Software
!!! tip
	To manually interface with the LG290P GNSS module, users can utilize the [QGNSS software provided by Quectel](#qgnss-software). This method is recommended due to the unique data structure of the UART command messages, utilized to configure the LG290P module.

	??? warning "Windows Only"
		Currently, the QGNSS software is only available for Windows operating systems.

	??? success "Windows, MacOS, or Linux"
		For users with computers that run on MacOS or Linux, we have found alternative software option for viewing the data from the NMEA messages. However, this GUI interface is currently limited to only receiving UART messages and cannot send messages to configure the LG290P module.

		- :material-github: [GitHub Repository](https://github.com/semuconsulting/PyGPSClient)
		- [Installation Instructions](https://github.com/semuconsulting/PyGPSClient?tab=readme-ov-file#installation)
		- [PyPI Project](https://pypi.org/project/pygpsclient/)



### QGNSS Software
QGNSS is highly intuitive GNSS evaluation software that is easy to use, personalized, and compatible with leading Quectel technologies. The software allows users to define or apply GNSS product configurations for specific use cases. Saving, restoring, or sharing configurations between different products and updating the module's firmware are easy. The software supports product evaluation with a choice of views to observe static and dynamic behavior of the connected a Quectel GNSS receiver.

<div align="center" markdown>

	[:octicons-download-16:{ .heart } Download the QGNSS Software *(v2.1)* from Quectel](https://www.quectel.com/download/qgnss_v2-1_en/){ .md-button .md-button--primary target="blank" }

</div>

??? warning "Windows Only"
	Currently, the QGNSS software is only available for Windows operating systems.


#### Connecting to the LG290P
In order to connect to the LG290P properly, users will need to specify the settings of the UART port.

<figure markdown>
[![Configure UART Settings](./assets/img/hookup_guide/qgnss-uart_settings-button.png){ width="400" }](./assets/img/hookup_guide/qgnss-uart_settings-button.png "Click to enlarge")
<figcaption markdown>
Click the <kbd>:material-cog:</kbd> button to configure the UART settings.
</figcaption>
</figure>

Before users can connect to the RTK Postcard, they will need to specify the connection settings in QGNSS. Once configured, users can select the ++"OK"++ button and QGNSS will automatically attempt to connect to the GNSS module.

- Select the `LG290P(03)` from the drop-down menu to configure the `Model` of the GNSS module being connected.
- Below, is a list of the default settings for `UART` ports of the LG290P. These settings should be selected in the `Device Information` menu, unless configured differently.
- When connecting through the USB-C connector, under the `Port` option, select the port labeled with channel `B` from the drop-down menu.


<div class="grid" markdown>

<div markdown>

<figure markdown>
[![UART Settings in QGNSS](./assets/img/hookup_guide/qgnss-uart_settings.png){ width="400" }](./assets/img/hookup_guide/qgnss-uart_settings.png "Click to enlarge")
<figcaption markdown>
From the available `COM` ports for the CH342, select the port labeled `B` to access the LG290P GNSS receiver. Users will also need to specify the settings for the UART port.
</figcaption>
</figure>

</div>


<div markdown>

!!! info "LG290P - Default Settings"
	The UART ports of the LG290P GNSS module will have the following default configuration:

	- Baudrate: 460800bps
	- Data Bits: 8
	- Parity: No
	- Stop Bits: 1
	- Flow Control: None

</div>

</div>



#### Configure the LG290P
By default, the UART ports are configured to transmit and receive `NMEA 0183` and/or `RTCM 3.x` messages. These messages are generally used for transmitting PNT data; and providing or receiving RTK corrections, respectively. Quectel also implements a system of proprietary messages (`PQTM`) for users to configure the LG290P, following the data format of the `NMEA` protocol.

???+ terminal "Data Format - PQTM Messages"
	The expected structure of the data in the proprietary PQTM messages is shown below:

	<figure markdown>
	[![NMEA data structure](./assets/img/hookup_guide/nmea_protocol.png){ width="600" }](./assets/img/hookup_guide/nmea_protocol.png "Click to enlarge")
	<figcaption markdown>
	The data structure of Quectel messages for the `NMEA` protocol.
	</figcaption>
	</figure>

	`<Checksum>`:

	- Checksum field follows the checksum delimiter character `*`.
	- Checksum is the 8-bit exclusive OR of all characters in the sentence, including `,` the field delimiter, between but not including the `$` and the `*` delimiters.

	`<CR>` & `<LF>`: Carriage return; followed by a new line

	- Depending on the terminal emulator, these may be options configured in the program settings.
	- Otherwise, users may need to add the `\r` and `\n` characters at the end of the message.

In the QGNSS software, users can click on the ++"Advance"++ button, at the bottom of the `QConsole` window, to configure the settings for the messages sent to the LG290P. Selecting `NMEA` and `CRLF` from the drop-down menu of the **Checksum Type** and **Suffix** options, will automatically calculate and append the `<checksum>` value, carriage return, and line follow to the end of the message entered in the **Data Input** field.

<figure markdown>
[![NMEA message setting](./assets/img/hookup_guide/qgnss-message_settings.png){ width="600" }](./assets/img/hookup_guide/qgnss-message_settings.png "Click to enlarge")
<figcaption markdown>
The settings for the messages transmitted from the QConsole.
</figcaption>
</figure>


???+ tip "Display the QConsole Toolbar"
	There is a toolbar for the QConsole, which has a bunch of tools that users may find useful. This includes, a search function, scroll-lock button, pause/clear the message feed, etc. To open/close the toolbar inside the QConsole, ++"right-click"++ on the mouse and select the `Show Tool` option from the drop-down menu or utilize the keyboard shortcut: ++ctrl++ + ++q++.

	<figure markdown>
	[![QConsole Toolbar](./assets/img/hookup_guide/qgnss-toolbar.gif){ width="400" }](./assets/img/hookup_guide/qgnss-toolbar.gif "Click to enlarge")
	<figcaption markdown>
	++"Right-click"++ on the mouse and select the `Show Tool` option, inside the QConsole.
	</figcaption>
	</figure>

??? example "Example - `PQTMCFGUART` Message"
	As an example, try utilizing the `PQTMCFGUART` PQTM message. Enter `$PQTMCFGUART,R*` into the **Data Input*** field of the QConsole. DOn't forget to select the `NMEA` and `CRLF` options from ++"Advance"++ settings menu. If entered and configured properly, the value `36` should pop up in the **Checksum** field of the QConsole; then, click on the <kbd>:material-send:</kbd> button to send the message.

	``` bash
	$PQTMCFGUART,R*
	```

	Once the message has been sent, keep a close watch of the messages in the console. It may help to click on the <kbd>:octicons-unlock-16:</kbd> button to disable auto-scrolling, when trying to locate the message response. Additionally, the response may not appear right away, it could be appended to the end of the next data packet, as shown in the image below.

	<figure markdown>
	[![PQTM demo](./assets/img/hookup_guide/qgnss-pqtm_message.png){ width="400" }](./assets/img/hookup_guide/qgnss-pqtm_message.png "Click to enlarge")
	<figcaption markdown>
	Example of utilizing the Quectel PQTM messages in the QConsole.
	</figcaption>
	</figure>


### PyGPSClient
!!! warning "Software Limitations"
	With this software, users will only be able to view the data from the NMEA messages and connect to an NTRIP caster. Users will not be able to configure the LG290P module with the built-in console.

As an alternative to QGNSS, for users with computers that run on MacOS or Linux, we recommend [PyGPSClient](https://github.com/semuconsulting/PyGPSClient) as an option for viewing the data from the NMEA messages and connecting to an NTRIP caster. However, users should be aware that this GUI interface is currently limited to only receiving UART messages and cannot send messages to configure the LG290P module.

??? info "Resources"
	For additional information, users can refer to the following resources for the PyGPSClient software:

	- :material-github: [GitHub Repository](https://github.com/semuconsulting/PyGPSClient)
	- [Installation Instructions](https://github.com/semuconsulting/PyGPSClient?tab=readme-ov-file#installation)
	- [PyPI Project](https://pypi.org/project/pygpsclient/)


#### Installation
There are a variety of [installation methods](https://github.com/semuconsulting/PyGPSClient?tab=readme-ov-file#installation) detailed in the GitHub repository's `README.md` file. However, we recommend utilizing the `pip` installation method.

!!! terminal "Installation Commands"
	Depending on how Python is installed on the computer, one of the following commands should allow users to install the software.

	- 
		``` bash
		python3 -m pip install pygpsclient
		```
	- 
		``` bash
		pip install pygpsclient
		```

	!!! info "System Requirements"
		This installation method requires an internet connection. Additionally, users will also need administrative privileges *(or root access `sudo`)* for the installation.


#### Connecting to the LG290P
Before users can connect to the RTK Postcard, they will need to specify the settings of the UART port in PyGPSClient. Once configured, users can select the <kbd>:material-usb:</kbd> button and PyGPSClient will automatically attempt to connect to the GNSS module.

- Below, is a list of the default settings for `UART` ports of the LG290P. These settings should be selected in the configuration menu.
- For the `Serial Port`, select the port labeled with channel `B` from the drop-down menu.


<div class="grid" markdown>

<div markdown>

<figure markdown>
[![UART Settings in PyGPSClient](./assets/img/hookup_guide/pygpsclient-uart_settings-small.png){ width="400" }](./assets/img/hookup_guide/pygpsclient-uart_settings-small.png "Click to enlarge")
<figcaption markdown>
Specify the settings for the UART port in QGNSS.
</figcaption>
</figure>

</div>


<div markdown>

!!! info "LG290P - Default Settings"
	The UART ports of the LG290P GNSS module will have the following default configuration:

	- Baudrate: 460800bps
	- Data Bits: 8
	- Parity: No
	- Stop Bits: 1
	- Flow Control: None

</div>

</div>


### Terminal Emulator
Another viable option for connecting to the RTK Postcard, is to utilize a [terminal emulation program](https://learn.sparkfun.com/tutorials/112). While reading the data sent from the LG290P is relatively trivial, users will need to be more selective when choosing an emulator to configure the LG290P module on the RTK Postcard. This is due to the unique data structure of the proprietary messages that Quectel implements to configure the LG290P *(see the [**Configure the LG290P**](#configure-the-lg290p) section, above)*.

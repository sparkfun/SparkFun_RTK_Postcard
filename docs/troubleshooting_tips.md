---
icon: sfe-logo
---

!!! warning "Need Help?"
	If you need technical assistance or more information on a product that is not working as you expected, we recommend heading over to the [SparkFun Technical Assistance](https://www.sparkfun.com/technical_assistance) page for some initial troubleshooting.

	<article style="text-align: center;" markdown>
	[SparkFun Technical Assistance Page](https://www.sparkfun.com/technical_assistance){ .md-button .md-button--primary }
	</article>

	If you can't find what you need there, the [SparkFun GNSS Forum](https://community.sparkfun.com/c/global-positioning-system-gps/96) is a great place to ask questions.

	!!! info "Account Registration Required"
		If this is your first visit to our forum, you'll need to create a [Forum Account](https://community.sparkfun.com/signup) to post questions.


## Antenna Issues
At a minimum, we recommend utilizing an active L1/L2/L5 antenna with the LG290P. Some customers have reported that the LG290P remains in an `RTK Float` status, when utilizing GNSS antennas that don't meet these specifications. This is because the GNSS receiver is having issues resolving the ambiguities of the signals not being provided from the GNSS antenna. To resolve this issue, mask the signals and satellites in the GNSS receiver configuration. Limit the signals and satellites to only the capabilities of the GNSS antenna.


<!-- QR Code for Hookup Guide (Displayed when printed) -->
<article style="text-align: center;" markdown>
![QR code to the hookup guide](./assets/img/qr_code/hookup_guide.png){ .qr }
</article>

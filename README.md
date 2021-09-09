# Private-AstroRaspberryPi

/lib/udev/rules.d/99-asi.rules

# Other mods:
- modified /etc/dhcpcd.conf:
	# Prefer wlan over eth for internet access
	interface wlan0
	metric 100

- (!) repository for RPi: https://indilib.org/download/raspberry-pi.html
	contains indi, kstars, phd2 etc
	see https://www.astroberry.io/docs/index.php?title=Astroberry_Server
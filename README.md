# Private-AstroRaspberryPi

/lib/udev/rules.d/99-asi.rules

# Other mods:
- modified /etc/dhcpcd.conf:
	# Prefer wlan over eth for internet access
	interface wlan0
	metric 100
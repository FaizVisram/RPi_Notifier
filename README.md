RPi_Notifier
================

Display notifications for a Raspberry Pi. 

Currently, notifications appear on LEDs connected to GPIO pins.

Features
================

* Supports multiple LEDs
* Show warnings for 
	* high CPU temperatures
	* low disk space
	* low RAM
	* no network connection
	* no Internet connection
* Doesn't depend on other packages; supports the standard /sys/class/gpio driver

_Tested to work with Raspbian Wheezy found here: http://www.raspberrypi.org/downloads_

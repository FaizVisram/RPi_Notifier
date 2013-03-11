RPi_Notifier
================

Display notifications for a Raspberry Pi. 

Currently, notifications appear on LEDs connected to GPIO pins.

_Tested to work with Raspbian Wheezy found here: http://www.raspberrypi.org/downloads_


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


Usage
================

By default, the notifier script only runs one iteration of all checks. This is useful for something like Cron where it will be scheduled to execute.

To loop constantly in the background, use the standalone option (-s, --standalone).

_Requires root privileges._

# Tineco Thermostat

More information : http://tineco.ido4pro.com

[Version française](https://github.com/ido4pro/tineco/blob/master/LISEZMOI.md)

[![Analytics](https://ga-beacon.appspot.com/UA-77079936-1/tineco-thermostat/readme)](https://github.com/ido4pro/tineco-thermostat)

## Hardware

Tineco is a WIFI thermostat to control your boiler system or one electrical heater.

![electronic board](images/electronic-board-small.png)

Tineco is based on the esp8266 module. 

This wifi module has a great SDK to allow easy firmware modification with an OTA process.

Tineco has an internal tem/humidity sensor, a external one-wire bus to connect a DS1820 sensor, a 10 A relay with current sensor.

Tineco has an integrated convertor (220v) to power the electronic boad.

A hardware watchdog detect failure of the firmware and restart automaticaly the esp8266 module.

![hardware](images/tineco-hardware.png)

## IDE

Start a full preset ide with compiler in one line  : https://github.com/ido4pro/tineco-sming-ide-docker


## Software

The source code is written in C++ and based on the sming framework : [sming](https://github.com/SmingHub) et le language C++. 

Start with this project : https://github.com/ido4pro/tineco-starter-project

## Schematics

![esp8266](images/esp8266-core.png)

![power](images/power-AC-DC.png)

![temperature humidity sensor](images/tem-hum-sensor.png)

![one wire bus](images/one-wire-bus.png)

![relay with current sensor](images/relay-with-current-sensor.png)

![power](images/zero-detection.png)

![power](images/current-input.png)


## Author

Stéphane GUILLY - stephane.guilly@ido4pro.com
Thierry COUSIN - thierry.cousin@ido4pro.com

Contact us if you are interresting to buy a product






 
 
 





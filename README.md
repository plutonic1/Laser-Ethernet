# Laser-Ethernet

In this repo I will track the progress of my laser ethernet project. The goal is to design and build a device, that
transmits ethernet frames over a laser.

## first try

I tried to connect 2 Raspberry PIs via serial connection using pppd (see sources). Then I replaced the wired connection
with a simple laser transceiver. Transmission speed was ~10-20 kBit/s.
ToDo: Add schematics

![picture of the Raspberry Pi experiment](https://raw.githubusercontent.com/plutonic1/Laser-Ethernet/master/images/rpi_experiment.jpg "picture of the Raspberry Pi experiment")


## Sources

- [http://blog.svenbrauch.de/2017/02/19/homemade-10-mbits-laser-optical-ethernet-transceiver/](http://blog.svenbrauch.de/2017/02/19/homemade-10-mbits-laser-optical-ethernet-transceiver/)
- [https://www.mikrocontroller.net/articles/Lichtsensor_/_Helligkeitssensor](https://www.mikrocontroller.net/articles/Lichtsensor_/_Helligkeitssensor)
- [https://vjordan.info/log/fpga/raspberry-pi-3-ethernet-over-serial.html](https://vjordan.info/log/fpga/raspberry-pi-3-ethernet-over-serial.html)
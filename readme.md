﻿# OGN-Airtracker

Live plane tracker based on [Open Glider Network project](http://www.glidernet.org/).

## Hardware

Hardware is a flavor of the [Cheap Do-It-Yourself OGN tracker](http://wiki.glidernet.org/ogn-tracker-diy).

The latest version OGN-Airtracker assembly contains:

* STM32F103C8T6 CPU board with ARM STM32 Cortex-M3 CPU
  [@eBay](http://www.ebay.com/itm/321569700934)
* HOPERF RFM69HW transceiver
  [@Anarduino](http://www.anarduino.com/miniwireless/)
* SMA-female socket with pigtail
* SW868-WT100 868MHz 50ohm antenna with SMA-male right angle connector
  [@AliExpress](http://www.aliexpress.com/item/NiceRF-Rubber-Antenna-SW868-WT100-Wireless-RF-Antenna-868MHz/32319847439.html)
* Adhesive copper foil tape for antenna counter-weight
  [@eBay](http://www.ebay.com/itm/161170293355)
* VK2828U7G5LF GPS module
  [@eBay](http://www.ebay.com/itm/251959460965)
* LCD for Nokia 5110
  [@eBay](http://www.ebay.com/itm/221475096725)
* 18650 Li-Ion cell battery
* Micro USB 18650 Lithium Battery Charging Board with undervoltage protection
  [@eBay](http://www.ebay.com/itm/251888669022)
* 18650 battery holder
  [@eBay](http://www.ebay.com/itm/361262848840)
* Toggle on/on switch
  [@eBay](http://www.ebay.com/itm//111624235328)
* Some female to female dupont jumper wire cables
  [@eBay](http://www.ebay.com/itm/390925108344)
* Some toroidal ferrite rings for EMC filtering
  [@eBay](http://www.ebay.com/itm/271876448943)


## Software

Software is again a fork of the [Cheap Do-It-Yourself OGN tracker sw](https://github.com/glidernet/diy-tracker)
enhanced with LCD display and buttons control.

For now in [separate module](https://github.com/peclik/diy-tracker/tree/lcd).


## Case

See [case folder](case/readme.md).


## License

The code is copyrighted by Open Glider Network developers including:
* [Richard Pecl](https://github.com/peclik)
* [Paweł Jałocha](https://github.com/pjalocha)
* [Wojtek Buczak](https://github.com/wbuczak)

The code is licensed under a [GNU General Public License Version 3](http://www.gnu.org/licenses/gpl-3.0.html).

Case designs are created by:
* [Richard Pecl](https://github.com/peclik)

The designs are licensed under a [Creative Commons
  Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

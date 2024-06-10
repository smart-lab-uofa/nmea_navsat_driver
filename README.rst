nmea_navsat_driver
===============

ROS driver to parse NMEA strings and publish standard ROS NavSat message types. Does not require the GPSD daemon to be running.

**Changes Needs to be Made to run on Holybro M8N GPS Module**

**To run this package with M8N driver, you need to modify the port in u-center(can be downloaded from the official website) under view->view configuration->PRT. The default port is 38400 Hz, but due to some reason the default port in our case was 230400 Hz. You need to modify the Protocol in and out the same window to NMEA.**

API
---
nmea_navsat_driver/src/libnmea_navsat_driver/nodes/nmea_serial_driver.py
This package has no released Code API.

The ROS API documentation and other information can be found at http://ros.org/wiki/nmea_navsat_driver

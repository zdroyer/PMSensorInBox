# PMSensorInBox

Adapter to fit Luftdaten.info prticulates sensor into a Hensel DK 0400 G junction box, which is quite a nice looking thing and is certified IP66 and can be used outdoors.
The initial idea of the insert came from Richard Körber and his project: https://www.thingiverse.com/thing:2775946 , but I moved the temperature sensor outside of the box to avoid the problem of higher than actual temperature values.

The file can be open and edited in FreeCAD, v19, where you can export AMF/STLs, 3d-print it and assemble the device.

BOM:
1 x PM Sensor SDS011
1 x Lolin NodeMCU ESP8266 V3
1 x DHT22 or BME280  (temerature and humidity sensor)
4 x Dupont connection cable (see luftdaten.info)
1 x Micro USB cable (power)
1 x USB power supply

1 x Hensel DK 0400 G junction box
9 x M3x10 cheese head screws
2 x M3x30 cheese head screws
5 x M3x10 countersunk head screws
1 x M3x10 plastic screw for BME280 or 1 x M3x8 cheese head screw for DHT22


The cable junction box used for the project: https://www.hensel-electric.de/en/produkte/index.php?IdProduct=12393
(there you can find also the simplified STEP files of this and other junction boxes)

I'm not anyhow connected with Hensel - the only reason I use it in the project is the availability of the box in the DIY shop in my area.


## License

This project is licensed under the [Creative Commons - Attribution - Non-Commercial - Share Alike](http://creativecommons.org/licenses/by-nc-sa/3.0/) license.
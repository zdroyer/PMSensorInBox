# PMSensorInBox

This is a FreeCAD project of a 3D printable adapter that makes the http://luftdaten.info particulate matter sensor fit into a Hensel DK0400G junction box, which is quite a nice looking thing, is IP66 certified and can be used outdoors.
The initial idea of the insert came from Richard Körber and his project: https://github.com/shred/dustycase . The main difference is the different box  and the temperature sensor place - I moved it outside of the box to avoid the too high temperature reading bug.

The adapter can be used with either DHT22 or BME280 temperature sensor, but only one at time.

The file can be open and edited in FreeCAD, v19, where you can export STLs, 3d-print it (4 instances of the M3x6 spacer, single instance of all the other solids) and assemble the device.
Although the current version of the project is printed (PLA and PET, Prusa MK3*) and successfully tested, I realise the model is not perfect. Please feel free to criticise, report a bug or (preferred) make it nicer/fancier/better - all PRs are very welcome!

## BOM:
1 x PM Sensor SDS011  
1 x Lolin NodeMCU ESP8266 V3  
1 x DHT22 or BME280  (temperature and humidity sensor)  
4 x Dupont connection cable (see http://luftdaten.info)  
1 x Micro USB cable (power)  
1 x USB power supply  

1 x Hensel DK 0400 G junction box  
9 x M3x10 cheese head screws  
2 x M3x30 cheese head screws  
5 x M3x10 countersunk head screws  
1 x M3x10 plastic screw for BME280 or 1 x M3x8 cheese head screw for DHT22  

The cable junction box used for the project: https://www.hensel-electric.de/en/produkte/index.php?IdProduct=12393
(there you can find also the simplified STEP files of this and other junction boxes)


## License

This project is licensed under the [Creative Commons - Attribution - Non-Commercial - Share Alike](http://creativecommons.org/licenses/by-nc-sa/3.0/) license.

## Disclaimer

I'm not anyhow connected with Hensel - the only reason I use it in the project is the availability of the box in the DIY shop in my area.

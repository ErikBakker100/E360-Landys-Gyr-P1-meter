# E360-Landys-Gyr-P1-meter
Schematic and interface description for reading the P1 port of a Landys Gyr E360

I changed the 10k pull up to a 1k pull up resistor. Since for the E360 the 10k did not work. The E360 uses a DSMR 5.0 interface, according the inerface description the data line should draw somewhere between 4mA and 10mA. The E360 uses an optocoupler as output. Whereby my former meter had already soem kind of pull up included. After the old meter had been replaced by the E360 the P1 interface did not work anymore.

Digging into the why, i discovered I had to use a pull up resistor (with the right value).

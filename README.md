Welcome To: I2C Isolation Breakout Hardware Repo!!
================================


##### Note: This is for the I2C Isolation Breakout Hardware Version 1 Branch

I2CisoBreakout Hardware Design Files in EAGLE. Not much to say, there are some custom parts will add Library after I clean it up!

Schematic Info
-------------------------
##### Basic schematic is split into sections

- Primary and Secondary sides for (both)
- ADUM6010 Isolated DC-DC converter with on chip transformers
- ADUM1251 I2C Isolation IC, bi-directional even on SCL
- Selectable voltage output (3.3 or 5v)
- Enable/Disable selector with tri state to allow external device to control

Board Layout Info
-------------------------
##### Form Factor based on Dangerous Prototypes SoB 50mmx50mm PCB size

- Standard 2.54mm pitch header and Grove style connector
- Power on bottom with isolation IC on top, Single supply
- Power IC can be switched on or off to all for isolation with separate supplies
- Selectable voltage output (3.3 or 5v)
- Enable/Disable selector with tri state to allow external device to control

Errata
-------------------------

##### Just a quick list of current issues
- Spacing between Primary and Isolation headers needs to be shrunk to better fit a bread board
- Clear silkscreen for power selection, and voltage selection on outputs

Firmware
-------------------------

- This is a "dumb" module and doesn't need any special firmware, In fact its a direct drop in series placement for I2C devices!!

Basic Usage
-------------------------

Usages of this device is very simple, it always for direct placement in series with an existing I2C Device, For those on the Grove style connector eco-system this breakout is extremely easy to use!

####Some of the commands are:
- Galvanic Isolation of I2C sensors
- Selectable Level shifter
- Allow for Hot/Swap or power down of I2C peripherals
- Power pullups (on host mainly) separately from VCC

License Info
-------------------------

<p>This is a fully open source project released under the CC BY license</p>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width: 0px;" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">I2C Isolation Breakout</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="www.sparkyswidgets.com" property="cc:attributionName" rel="cc:attributionURL">Ryan Edwards, Sparky's Widgets</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.<br />
Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="/portfolio-item/i2c-isolation-breakout/" rel="dct:source">http://www.sparkyswidgets.com/portfolio-item/i2c-isolation-breakout/</a>
# 5x5x5-Led-Matrix
<b>Build a 3D Led Matrix of your own!</b>
<img src="https://learn.adafruit.com/system/guides/images/000/000/586/medium800/neo_cube.jpg?1400136365"/>
<hr/>
## Introduction
<br/><br/>


<hr/>

## Tools and Materials
* <a href="http://www.adafruit.com/product/1734">125 x Thru-hole NeoPixels (if you get 130 you'll have spares in case you need them)</a>
* <a href="http://www.adafruit.com/product/1501">Trinket 5V<a/>
* <a href="http://www.adafruit.com/product/276">5V 2A power supply</a>
* <a href="http://www.adafruit.com/product/1683">On/Off Power button</a>
* <a href="http://www.adafruit.com/product/610">DC panel-mount jack</a>
* Wire
* Soldering Iron
* Solder
* Heat shrink tubing
* Wire Strippers
* 3D Printer<br/>
(Or you can go <a href="https://www.adafruit.com/wishlists/460">here</a> and buy all the materials from Adafruit 
<hr/>

## 3D Printed base
The base was designed to serve as a soldering template as well as a case for your electronics. It is required in the next steps so please print this first!
<img src="https://learn.adafruit.com/system/assets/assets/000/016/614/medium800/led_pixels_5x5x5_cube.png?1400140281"/>
<b><a href="https://learn.adafruit.com/system/assets/assets/000/016/618/original/5x5x5_Cube_Base.zip?1400186891">Download STL files</a></b>
<hr/>

## Wiring Layout
Each of the LEDs has 4 legs and a flat side. Getting these pins right is critical if you want it to work correctly. Below is a reference image showing what leg is what.
<img src="https://www.adafruit.com/images/970x728/1734-04.jpg"/>
<br/>
Now begin assembling the diagram below using the base we printed earlier as a reference and to hold the LEDs in place. Make sure the flat side of the LED matches the diagram below. 
<img src="https://learn.adafruit.com/system/assets/assets/000/016/619/medium800/led_pixels_adafruit_diagram.png?1400223434"/>
<br/>
After following the diagram above you should have something that resembles this (Please note this is a photo of the 3x3x3 version).
<img src="https://learn.adafruit.com/system/assets/assets/000/016/621/medium800/led_pixels_IMG_2046.jpg?1400224939"/>
<hr> 

## Soldering the LEDs
<br/><br/>


<img src="https://learn.adafruit.com/system/assets/assets/000/016/610/medium800/led_pixels_IMG_1953.jpg?1400139259"/>
<img src="https://learn.adafruit.com/system/assets/assets/000/016/611/medium800/led_pixels_IMG_1955.jpg?1400139269"/>
<hr/>

## Assembling the Controller
Solder short leads to the barrel connector.
<img src="https://learn.adafruit.com/system/assets/assets/000/016/693/medium800/led_pixels_IMG_2050.jpg?1400467458"/>

Solder one short ground connector to the on/off switch. The other lead on the switch will combine the ground from the NeoPixels and barrel connector. 

We will solder those after these two components are installed in the base.
<img src="https://learn.adafruit.com/system/assets/assets/000/016/694/medium800/led_pixels_IMG_2051.jpg?1400467466"/>

A bit of shrink-tube makes things look nice and can help prevent shorting.
<img src="https://learn.adafruit.com/system/assets/assets/000/016/695/medium800/led_pixels_IMG_2055.jpg?1400467814"/>
<hr/>

Install the barrel connector and on/off switch... a little hot glue on both will make things permanent.
<img src="https://learn.adafruit.com/system/assets/assets/000/016/696/medium800/led_pixels_IMG_2064.jpg?1400467892"/>

After installing the two components you can finish soldering power and ground through the on/off switch. 

The end-product would look something like this... I made the mistake of cutting some of my wires a little short.

~~I decided to combine the ground connections on the on/off switch and power on the barrel connector. 

bare wire = pin #0 (NeoPixel signal in)<br/>
yellow = power (BAT pin)<br/>
black = ground<br/>

~~If everything checks-out, glue the base cover in place and lets pump some electrons through this thing!~~
<img src="https://learn.adafruit.com/system/assets/assets/000/016/697/medium800/led_pixels_IMG_2103.jpg?1400467979"/>

## Example Code

For quick testing of your new cube you can run the 'strandtest' example code provided by the Adafruit_Neopixel library

<hr/>

## Credits
<a href="https://learn.adafruit.com/free-wire-3x3x3-neopixel-cube/source-code">Adafruit (Original creator of the Tutorial)</a>

# TPRCB
Toilet Paper Roll Counter Box

## Why
As I was sitting on the toilet the other day, I discovered we had no toilet paper left. Luckily I survived the event, but figured that this could never happen again!

Therefore I made a box that counts the number of toilet paper rolls, which also warns me if we're running low. Everything done with the help from [Home Assistant](https://www.home-assistant.io/) and [ESPHome](https://esphome.io/) 🎉🤩

![box](https://github.com/petrepa/TPRCB/blob/master/Photos/box.jpeg)

If we have less than 4 rolls, we get a subtle warning from the box
![warning]()

And if we have less than 2(!) rolls left, the box goes into EMERGENCY mode🚨🚨🚨
![emergency]()


## Build
Built this using:
* [NodeMCU](http://www.nodemcu.com/index_en.html) V3
* HX711 and a load cell
* Gilde Box
* [Clas Ohlson Wooden Box](https://www.clasohlson.com/no/Trekasse-med-h%C3%A5ndtak/Pr441449000)
* 12V PSU
* Barrel Socket
* WS2812 LED Strip

### Build process
The new box:
![box_new](https://github.com/petrepa/TPRCB/blob/master/Photos/box_new.jpg)

Cutting of Gilde for the plate inside the box:
![gilde_cutting](https://github.com/petrepa/TPRCB/blob/master/Photos/gilde_cutting.jpg)

Checked that the plate fits in the box:
![fits](https://github.com/petrepa/TPRCB/blob/master/Photos/fits.jpg)

The hole for the barrel plug:
![barrel_hole](https://github.com/petrepa/TPRCB/blob/master/Photos/barrel_hole.jpg)

Didn't have a drill that fit the barrel plug, so decided to make a bigger hole, and then 3D-print an adapter for the plug:
![adapter](https://github.com/petrepa/TPRCB/blob/master/Photos/adapter.jpg)

Mounted the load cell to the plate, and another plate as the bottom:
![load_cell](https://github.com/petrepa/TPRCB/blob/master/Photos/load_cell.jpg)
![weight_plate](https://github.com/petrepa/TPRCB/blob/master/Photos/weight_plate.jpg)

Placement of the LED Strip:
![led_strip](https://github.com/petrepa/TPRCB/blob/master/Photos/led_strip.jpg)

## Schematics
![finised]()

## Code
The code is made in ESPHome, a super easy way to make code for sensor and other stuff for Home assistant
[Here](https://github.com/petrepa/TPRCB/blob/master/toilet_paper.yaml) it is!

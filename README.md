# VOID9
*A 3x3 handwired macropad*

![VOID9](https://i.imgur.com/Db82OaX.jpg)

The VOID9 is a 3d printed, handwired, 4x4 macropad running QMK Firmware on a Pro Micro controller.

I suggest printing the case using a 0.4 mm nozzle, supports are not needed for any of the parts.

You might want/need to use small dabs of hot glue to secure the switches in the plate depending on how well calibrated your printer is(if you're generous with it, it will add to the weight of the keyboard and it might change the feel of it).

Dont overtighten the screws as threads might get stripped.

# Bill Of Materials

* 3d printed case parts
* 9 x Cherry MX style mechanical switches
* 9 x diodes ([tme.eu](https://www.tme.eu/ro/en/details/1n4148-dio/tht-universal-diodes/diotec-semiconductor/1n4148/))
* 9 x keycaps of choice
* 1 x Pro Micro ([Aliexpress](https://www.aliexpress.com/item/32902569443.html))
* 0.5 mm wire
* hotglue
* 4 x M3x10 Allen head bolts ([tme.eu](https://www.tme.eu/ro/en/details/m3x10_d912-a2/bolts/kraftberg/) / 13mm overall length, 5,5mm diameter head)
* 4 x 8mm bumpons
* 1 x 3 WS2812b LEDs 
# Handwiring guide

I've also put together a pretty visual handwiring guide for the VOID9, that you can browse over [here](https://victorlucachi.ro/journal/void9-wiring-guide/).

| ![](https://i.imgur.com/MHTt02w.jpg) 	| ![](https://i.imgur.com/TzdhlCM.jpg) 	| ![](https://i.imgur.com/vTpQaXI.jpg) 	|
|---------------------------------------	|---------------------------------------	|---------------------------------------	|

# Pin assignment

    ROW0    ROW1    ROW2
    F4      F5      F6
    
    
    COL0    COL1    COL2  LED Data
    D1      D0      D4    B2

# QMK Fork

A fork containing the QMK config files can be found [here](https://github.com/victorlucachi/qmk_firmware/tree/master/keyboards/handwired/void9). Edit them to suit your own needs and build the firmware following the QMK docs.

If you plan on using the VIA keymap dont forget to download the json definitions file linked in this repository.

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

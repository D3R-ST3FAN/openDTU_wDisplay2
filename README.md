# openDTU_wDisplay2 [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

* Small PCB for [openDTU](https://github.com/tbnobody/OpenDTU)
* Based on idea/ realization of [breakout board](https://github.com/dokuhn/openDTU-BreakoutBoard)
* 2nd version with much smaller PCB [1st version](https://github.com/SteffMUC/openDTU_wDisplay)
* The PCB has the ESP32 on backside, Display and nRF24l01 on frontside.
* Dedicated case available in [openscad](https://github.com/SteffMUC/openDTU_wDisplay2/tree/main/openscad) directory
* Configuration file [nodemcu_esp32.json](https://github.com/tbnobody/OpenDTU/blob/master/docs/DeviceProfiles/nodemcu_esp32.json) available in [openDTU](https://github.com/tbnobody/OpenDTU), please select "Generic NodeMCU 32 with SSD1306" as profile
* In case you struggle how to configure [openDTU](https://github.com/tbnobody/OpenDTU), the documentation can be found here [openDTU Display documentation](https://github.com/tbnobody/OpenDTU/blob/master/docs/Display.md)
* The PCB is designed to work with ESP32S NodeMCU (38 Pins) e.g. [Amazon](https://www.amazon.de/gp/product/B0BF5NRF8H/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)

## Picture of model:
<p float="left">
  <img src="kicad_board3d.jpg" alt="Board Model" width="300"/>
</p>

## Final printed case with display mounted on the side of a small IKEA Besta cupboard:
<p float="left">
  <img src="pics/IMG_0781.jpg" alt="Final assembly" width="200"/>
</p>

## PCB assembly:
<p float="left">
  <img src="pics/IMG_0747.jpeg" alt="PCB" width="200"/>
  <img src="pics/IMG_0748.jpeg" alt="PCB" width="200"/>
  <img src="pics/IMG_0749.jpeg" alt="PCB" width="200"/>
  <img src="pics/IMG_0750.jpeg" alt="PCB" width="200"/>
</p>



## History:

* 2023-02-28: boards received, soldered, working reliable, pics in picture folder, case currently in progress - not yet perfectly fitting 

* 2023-03-01: Final printing of case done, got some requests for spare PCBs, all spare PCBs now gone, if you need a PCB, you can easily upload the gerber zip file on any PCB manufacturer, e.g. PLCPCB (10 pieces, with customs to Germany in 2 weeks roughly 14 EUR).

* 2023-03-11: Accepted pull request from @Nightreaver, thanks for the contribution, backside silk screen now mirrored, nRF footprint changed by @Nightreaver to support nRF+ with antenna (Note: openscad case not adapted and currently not planned to be adapted)

In case you are looking for a cheap source for the capacitors, I ordered mine with Christians_Shop at [Amazon](https://www.amazon.de/gp/product/B01MTSDA58/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) (they have a direct website as well).


## 3D Print:
Everything can be printed without support, expect for the ikea holder:
<p float="left">
  <img src="pics/IMG_0780.jpg" alt="Ikea holder with support structure" width="200"/>
</p>

## Known limitations: 
* Backside silkscreen is not mirrored, in Kicad, still needs to be fixed, result is mirrored text on backside (for new orders). --> Fixed now
* If you print the case: The holders for the PCB are not yet perfectly aligned (need 0.5mm adjust), I "clipped" 3 of them away to avoid reprinting.








 

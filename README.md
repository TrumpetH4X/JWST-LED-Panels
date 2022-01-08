# JWST LED Wall Panels

<img src="/Media/IMG_2971.jpeg" width="75%" height="75%">

## Overview
Thingiverse project link:
https://www.thingiverse.com/thing:5163052

I've always enjoyed the honeycomb mirror arrangement of [NASA's James Webb Space Telescope (JWST)](https://jwst.nasa.gov/content/webbLaunch/index.html). To commemorate the telescope's launch on December 22, 2021, I created a set of DIY Nanoleaf LED wall panels inspired by the telescope's primary mirror. 

The LED Display is composed of 18 3D-printed hexagonal cells, with 18 3mm acrylic light diffusers glued to the top. Microcontroller is a Wemos D1 Mini running [WLED](https://github.com/Aircoookie/WLED). Each cell has 12 LEDs, divided into two LEDs per side (216 LEDs total). 216 x ~60mA x 5V = ~64.8W peak total power draw. Total display size is ~26" long.

## Demo Videos
#### JWST LED Panels Demo #1
[![JWST LED Panels Demo #1](https://img.youtube.com/vi/lVMFP3fJyJ0/0.jpg)](https://youtu.be/lVMFP3fJyJ0)

#### JWST LED Panels Demo #2
[![JWST LED Panels Demo #2](https://img.youtube.com/vi/Et5v4fz4g6E/0.jpg)](https://youtu.be/Et5v4fz4g6E)

## Parts List
|Quantity|Item|Notes|
|----|-------|-------|
|2|[WS2812B Addressable RGB LED Strip, 30 pixels/m](https://www.amazon.com/gp/product/B01CDTECSG/ref=ox_sc_act_title_1?smid=A35UAT07QG3EC6&th=1)|These strips draw around 60mA per LED, so size your power supply accordingly|
|1|[Wemos D1 Mini](https://www.amazon.com/gp/product/B07W8ZQY62/ref=ewc_pr_img_2?smid=A3KCMC2VCXFGL9&th=1)||
|2-3|[JST 3-Pin Connectors, 20pk](https://www.amazon.com/ALITOVE-Female-Connector-WS2812B-SK6812-RGBW/dp/B071H5XCN5/ref=sr_1_3?dchild=1&keywords=3-wire+jst+connector&qid=1634795158&sr=8-3)| May not be necessary, if you want to make permanent connections instead|
|2-3| [Roll(s) of Black PETG](https://www.amazon.com/gp/product/B07TRPPGT7/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1)| I chose to use PETG for the structural properties. PLA would probably still work fine.
|3|[3pk White Acrylic Diffuser (3mm)](https://www.amazon.com/Acrylic-Plexiglass-Versatile-Strength-Plastic/dp/B083XQ2QS7/ref=sr_1_1?dchild=1&keywords=2mm+white+acrylic+diffuser+12x12+6pk&qid=1634798519&sr=8-1)| NOTE: You will need access to a laser cutter (or some other machinery) to cut these acrylic sheets. I have seen some projects that use a thin layer of white PLA as a diffuser instead of acrylic, your mileage may vary.
|1| Spool of solder
|1| Soldering Iron
|3| Rolls of assorted red, black, and green wire||
|1|[5V 15A Power Supply](https://www.amazon.com/gp/product/B08764XJ2M/ref=ox_sc_act_title_1?smid=AOTVD5RNGJU9R&psc=1)|If you choose to use more/less LEDs in your setup, you can adjust the power supply wattage as necessary.|
|2-3|Bottle(s) of your superglue of choice||
|2-3|Screws for wall-mounting

## Software
My Wemos D1 Mini is running [WLED](https://github.com/Aircoookie/WLED). I have 18 virtual LEDs set up, with 12 LEDs grouped to each.

## Assembly/Wiring
<img src="/Media/Screen Shot 2021-12-12 at 3.54.21 PM.png" width="50%" height="50%">
<img src="/Media/circuit_1.jpg" width="75%" height="75%">
<img src="/Media/IMG_2675.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2806.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2801.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2914.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2940.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2964.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2986.jpeg" width="75%" height="75%">
<img src="/Media/IMG_2991.jpeg" width="75%" height="75%">





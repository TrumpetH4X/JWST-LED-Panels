# JWST LED Wall Panels

<img src="/Media/IMG_2971.jpeg" width="500" height="500">

## Demo Videos
#### JWST LED Panels Demo #1
[![JWST LED Panels Demo #1](https://img.youtube.com/vi/lVMFP3fJyJ0/0.jpg)](https://youtu.be/lVMFP3fJyJ0)

#### JWST LED Panels Demo #2
[![JWST LED Panels Demo #2](https://img.youtube.com/vi/Et5v4fz4g6E/0.jpg)](https://youtu.be/Et5v4fz4g6E)

## Overview
I've always enjoyed the honeycomb mirror arrangement of [NASA's James Webb Space Telescope (JWST)](https://jwst.nasa.gov/content/webbLaunch/index.html | width = 10). To commemorate the telescope's launch on December 22, 2021, I created a set of DIY Nanoleaf LED wall panels inspired by the telescope's primary mirror. 

The LED Display is composed of 18 3D-printed hexagonal cells, with 18 3mm acrylic light diffusers glued to the top. Microcontroller is a Wemos D1 Mini running [WLED](https://github.com/Aircoookie/WLED). Each cell has 12 LEDs, divided into two LEDs per side. 216 LEDs total, 216 x 60mA x 5V = ~64.8W total power draw. Total display size is ~26" long.

## Parts List
|Quantity|Item|Notes|
|----|-------|-------|
|2|[WS2812B Addressable RGB LED Strip, 30 pixels/m](https://www.amazon.com/gp/product/B01CDTECSG/ref=ox_sc_act_title_1?smid=A35UAT07QG3EC6&th=1)|These strips draw around 60mA per LED, so size your power supply accordingly|
|1|[Wemos D1 Mini](https://www.amazon.com/gp/product/B07W8ZQY62/ref=ewc_pr_img_2?smid=A3KCMC2VCXFGL9&th=1)||
|2-3|[JST 3-Pin Connectors, 20pk](https://www.amazon.com/ALITOVE-Female-Connector-WS2812B-SK6812-RGBW/dp/B071H5XCN5/ref=sr_1_3?dchild=1&keywords=3-wire+jst+connector&qid=1634795158&sr=8-3)| May not be necessary, if you want to make permanent connections instead|
|3|[3pk White Acrylic Diffuser](https://www.amazon.com/Acrylic-Plexiglass-Versatile-Strength-Plastic/dp/B083XQ2QS7/ref=sr_1_1?dchild=1&keywords=2mm+white+acrylic+diffuser+12x12+6pk&qid=1634798519&sr=8-1)| NOTE: You will need access to a laser cutter (or some other machinery) to cut these acrylic sheets. I have seen some projects that use a thin layer of white PLA as a diffuser instead of acrylic, your mileage may vary. 
|1|[5V 15A Power Supply](https://www.amazon.com/gp/product/B08764XJ2M/ref=ox_sc_act_title_1?smid=AOTVD5RNGJU9R&psc=1)|If you choose to use more/less LEDs in your setup, you can adjust the power supply wattage as necessary.|
|2-3|Bottle(s) of your superglue of choice||



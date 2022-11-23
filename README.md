# arduino-lvgl-eez-demo

Clone https://github.com/goran-mahovlic/eez-framework-arduino.git into Arduino Library folder

In furure version we will make eez-framework as sumbmodule but for now do this

git clone https://github.com/goran-mahovlic/eez-framework-arduino.git

Install ESP32 or RP2040 platform in arduino

Add

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

https://github.com/earlephilhower/arduino-pico/releases/download/global/package_rp2040_index.json

install under board manager

Select and of those two

Install TFT_eSPI from Arduino >> Tools >> Manage libraries

Compile and it will not work

I do not know where to put lv_conf.h

ui.h cannot include hpp so that needs to be fixed...
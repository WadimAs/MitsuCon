# MitsuCon
Mitsubishi Heat Pump (Air Conditioner) Controller for Home Assistant

Arduino project to build Mitsubishi heat pump controller for Home Assistant. It has 2 branches, classic and native.

## Classic
This version is proven to working well on Home Assistant <=0.96. It has 2 parts:

* arduino sketch mitsubishi_heatpump_mqtt_esp8266_esp32.ino
* Home Assistant custom component mitsubishi_mqtt
  
Chris Davis has a very detail instruction here:
https://chrdavis.github.io/hacking-a-mitsubishi-heat-pump-Part-1/
https://chrdavis.github.io/hacking-a-mitsubishi-heat-pump-Part-2/

## Native: 
New development code without custom component. This branch is still in beta.


![Wemos D1 Mini Adapter](https://user-images.githubusercontent.com/44964969/51798270-c3392980-2242-11e9-8986-cffc5fe4d287.jpg)

This project is based on https://github.com/SwiCago/HeatPump library.

*Mitsubishi means Mitsubishi Electric, not Mitsubishi Heavy Industries.

## Credits
Thanks to all contributors especially:
* lekobob https://github.com/lekobob/mitsu_mqtt
* SwiCago https://github.com/SwiCago/HeatPump
* Hadley  https://nicegear.co.nz/blog/hacking-a-mitsubishi-heat-pump-air-conditioner/

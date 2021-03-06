# HomeKitLight

This is a followup to the [Christmas Light](https://github.com/AdySan/ChristmasLight) project. This time we’re controlling the light with Siri using HomeKit. More [here](http://adityatannu.com/blog/post/2015/12/13/ESP8266-based-HomeKit-accessories.html).

## Features

- Switch On/Off lights using Siri
- USB (phone changer) powered

 
</br>
<p align="center">
<img src="/images/circuit_bb.png" align="middle"alt="Circuit" height="600">
</p>
</br>
<p align="center">
<img src="/images/screenshot.png" align="middle" alt="webpage" height="600">
</p>
</br>


## Planned features

Just in case the HomeKit control fails, I’d like to have the original functionality as a backup.

- SPIFFS filesystem to store webpages
- File uploads to SPIFFS filesystem via browser
- OTA firmware update (using ArduinoOTA)
- mDNS to advertise host name
 

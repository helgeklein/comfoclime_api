# comfoclime_api
API Description for Zehnder ComfoClime 24/36 Airduino Interface

This is a documentation repository for the undocumented HTTP/JSON API of Zehnder ComfoClime 24 (Airduino/ESP32).

All data is transmitted unencrypted locally via HTTP interface from Zehnder ComfoClime App to the ComfoClime. Feel free to extend. If anyone has more information about ComfoClime sensor values and parameters, feel free to contact me.

The "Airduino" board seems to communicate with the compressor unit via modbus. There is communication with baud 9600 and typical "01 03 ..." / "01 06 ..." messages. But as there is no known register list, this is not very helpful.

Maybe somebody working at Zehnder Systems wants to contact me and give a little more details 😊 You've got a great, open-source-friendly API - that would convince lots of people in buying a Zehnder Comfo!

A integration for Home Assistant using this interface is available at:
https://github.com/msfuture/comfoclime

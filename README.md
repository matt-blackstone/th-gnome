# th-gnome
A simple temperature and humidity sensor platform built on esphome https://esphome.io/index.html using a SeedStudio XIAO esp32-c3 RISC-V MCU and Bosch BME280 sensor.

https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html

https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280/

Full PCB design here  https://oshwlab.com/matthew.blackstone/rack-sensor-esp_copy_copy.

SMD resistors and capacitors have two footprints to allow larger 1206 footprintes to be used for hand soldering. Hand soldering of the Bosch BME280 is not practical.

Configs for prometheus and MQTT will be povided. There seems to be a bug in esphome where both cannot be run at the same time.

A precompiled firmware image for prometheus is included in this repository since there is no customization required.

Flash instructions for prometheus. Use https://web.esphome.io/ Plug device to usb click connect and select the correct com port. Flash the bin file.

Cost: For a run of 10 boards including assembly except for the XIAO module which will need to be purchased seperatly and hand soldered.

JLCPCB PCB and assembly with shipping 126.55

10 Pcs Seeduino esp32c3 $89 on amazon. These can be found cheaper directly from SeedStudio($5 at time of writing) or other sources. Ensure antennas are included as they are required.

Total $216 per 10

<img src="Screenshot 2025-04-07 215142.png" width="50%" height="20%">

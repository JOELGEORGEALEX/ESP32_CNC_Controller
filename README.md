# ESP32_CNC_Controller_VERSION_1.0
## ESP32 based CNC controller board
* The idea is to build a ESP32 GRBL based CNC controller board
### Objectives
* To build a wireless CNC controller board, so that the machines will become system independent
* Support 4 axis motors,SD_CARD,Axis limits/TMC_SPI.
* Flash the espwroom32 module directly from USB with FTDI chip,without use of hardware buttons
* Upload gcodesfiles /send gcodes live to CNC machines with the help of any systems
* Correct the issues that will surely occur in version 1.
### Version 1 Board
* As always jumper wires hanging here and there,as part of errors & corrections. But efforts were not wasted. Finally one awkward looking working board :)

![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/esp1.jpeg "ESP32__CNC_BOARD")
### Eagle schematic
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/EAGLE.png "ESP32__CNC_BOARD")

![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/ESP32.JPG "ESP32__CNC_BOARD")
### FTDI 232RL flash circuit for ESPWROOM32
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/ftdiflash.JPG "ESP32__CNC_BOARD")
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/motordriv.JPG "ESP32__CNC_BOARD")
### Firmware flashing $###########Successsssss
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/arduinoesp.jpg "ESP32__CNC_BOARD")

### Web interface for axis control,GCODE upload
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/grblweb.png "ESP32__CNC_BOARD")
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/grblweb2.png "ESP32__CNC_BOARD")
![alt text for screen readers](https://github.com/JOELGEORGEALEX/ESP32_CNC_Controller/blob/main/esp2.jpeg "ESP32__CNC_BOARD")

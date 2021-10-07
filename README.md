# pxlDigit_PCB - A PCB for an easy scalable seven-segment display
![](https://github.com/Nerdiyde/pxlDigit_PCB/pictures/pxldigit.png)
The idea for the pxlDigit_PCB came to me while building the first version of the pxlDigit (article here:  **_[https://nerdiy.de/en/howto-elektronik-sieben-segment-ziffer-pxldigit-aus-ws2812-leds-bauen/](https://nerdiy.de/en/howto-elektronik-sieben-segment-ziffer-pxldigit-aus-ws2812-leds-bauen/)_**).

The pxlDigit is built up from individual WS2812 LED segments. To do this, the LEDs must first be glued into the 3D printed housing and then soldered together in there. This step in particular is not that easy due to the lack of space. : /

That’s why I designed the pxlDigit_PCB. The LEDs, the ESP8285 and the rest of the electronics can be installed on it. So you can first assemble, test and program the entire circuit board and then insert it into the 3D printed housing of the pxlDigit.

Thanks to the integrated USB-C connection, the Digit can also be supplied directly with power and, if necessary, the firmware can be programmed.

In addition, the following (optional) components can be installed on the PCB:

-   BME280 Climate sensor
-   TSL2591 Brightness sensor
-   MPR121 Touch sensor for up to 12 touch electrodes

**You can find more information about the software and detailed HowTo's in the following articles:**

- [PCB – Assembly of the pxlDigit_PCB](https://nerdiy.de/en/pxldigit/)
- [pxlBlck - Install and configure the pxlBlck plugin](https://nerdiy.de/en/howto-pxlblck-das-pxlblck-plugin-installieren-und-konfigurieren/)

### Trademarks
All third-party trademarks are the property of their respective owners. More infos here: https://nerdiy.de/en/warenzeichen/

### License
Unless otherwise stated, all works presented here and on Nerdiy.de that are not based on software/code are subject to the CC BY-NC-SA 4.0 license (attribution - non-commercial - dissemination under the same conditions 4.0 international).
You can find additional infos here: https://nerdiy.de/en/lizenz/

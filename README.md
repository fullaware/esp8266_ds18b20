# esp8266_ds18b20
This arduino code uses standard example libraries included with the ESP8266 board library and the latest OneWire library to poll the DS18b20 and provide back the temperature via URL in JSON format.

    {"temp":68.56}

The sensor I am using came from Amazon and are the external probes.  I chose these due to my desire to measure outdoor temperature and these are weather proof (Vktech DS18b20 Waterproof Temperature Sensors Temperature Transmitter):  
http://amzn.com/B00CHEZ250

Thanks to Adafruit for developing this great breakout board for the ESP8266:  
https://learn.adafruit.com/adafruit-huzzah-esp8266-breakout/overview

Thanks to Fritzing and the community for the wiring diagram!  
http://fritzing.org/projects/adafruit-huzzah-esp8266-breakout-and-ds18b20

![](https://github.com/fullaware/esp8266_ds18b20/blob/master/breadboard.jpg)

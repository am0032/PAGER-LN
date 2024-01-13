# PAGER-LN
This GitHub repository contains the working of a pager that I made in 2023. The pager utilizes a Telegram bot to send and receive data. It can scan for open WiFi networks and connect to them to transfer data, eliminating the need for a personal data plan. Additionally, the device's location can be tracked when an SOS signal is activated, as it can connect to open networks and most public WiFi networks include location information in the network name, providing a rough location(as in a store name or a public transport system name) and time which could be valuable to the law enforcement  in case of an emergency. This method of tracking is not reliable everywhere but can be used as a last resort.

Several other features are being implemented right now. The code is not yet made opensource and this is just a documentation.  

This project started as a gift.



The device uses a nodemcu board as the mainboard.




The final device is fit inside an old power bank shell as :  
![image](https://github.com/am0032/PAGER-LN/assets/123314532/6a241910-412f-47b5-b8fa-b9beaf5882a2)







This project uses the universal telegram bot library: https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot/blob/master/examples/ESP8266/FlashLED/FlashLED.ino

# PAGER-LN
This GitHub repository contains the code for a modern day pager. The pager utilizes a Telegram bot to send and receive data. It can scan for open WiFi networks and connect to them to transfer data, eliminating the need for a personal data plan. Additionally, the device's location can be tracked when an SOS signal is activated, as it can connect to open networks and most public WiFi networks include location information in the network name, providing a rough location(as in a store name or a public transport system name) and time which could be valuable to the law enforcers  in case of an emergency.This methond of tracking is not reliable everywhere but can be used as a last resort.

This project started as a gift for someone :)




The devce uses an ESP32 camera board as the pager hardware which reads and sends data.The ESP32 board is programmed by an arduino.

The connections between arduino and the esp 32 board is given below.









The project originated as an idea from this tutorial( https://randomnerdtutorials.com/telegram-control-esp32-esp8266-nodemcu-outputs/) which lets u control an led with the help of a telegram bot.

This project uses the univeral telegram bot library : https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot/blob/master/examples/ESP8266/FlashLED/FlashLED.ino

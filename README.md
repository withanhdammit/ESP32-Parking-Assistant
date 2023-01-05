## An ESP32 and WS2812b LED Parking Assistant

![Four_Bars_ExtraSmall](https://user-images.githubusercontent.com/55962781/202794373-1cdfc5d2-508c-4eeb-9bc8-bf75e5dc39d9.jpg)

A simple to build and use garage parking assistant using an ESP32 and WS2812b LEDs.  Using a low cost Wemos D1 Mini ESP32, a short strip of around 20-40 WS2812b LED pixels and TFMini-s LIDAR distance sensor, a visual parking assistant system for putting your car in the same location in the garage each time can easily be created.

### Please see the [wiki](https://github.com/Resinchem/ESP-Parking-Assistant/wiki) for full details on installation, configuration, settings and options.
If you just want to install the firmware for the ESP32, **[download the .bin file from the Releases page](https://github.com/withanhdammit/ESP32-Parking-Assistant/releases)**.  You do not need to download anything from the /src folder nor do you need to clone the repository.  Please follow the wiki instructions before asking questions about how to install the software.

Some key features of the system include:
- 4 variable distance parking zones, including a wake zone, an active zone, a parked zone and a backup zone.
- Each zone can have its own unique LED color, specified by the user
- The active zone has 5 different approach effects that can be used to visually show the car approaching the final parked position
- Automatically goes to standby or sleep mode and only awakens when a car enters the wake zone
- Supports any number of LED pixels, up to 100, and is designed so the LED strip can be mounted horizontally or vertically
- All options and settings made through a web interface
- Over-the-air firmware updates, with a manual OTA option available for uploading your own modified source code
- **Optional** MQTT integration so you can use the parking assistant in Home Assistant or other automation systems


**Note**: This repo only deals with the firmware/software application. For an overview of the build details and to see some of the features in use, please see this [YouTube video](https://youtu.be/HqqlY4_3kQ8).

Full step-by-step build instructions, including parts lists, wiring diagrams and more can be found in my blog article: [A New Parking Assistant using an ESP32 and WS2812b LEDs](https://resinchemtech.blogspot.com/2022/11/esp-parking-assistant.html)

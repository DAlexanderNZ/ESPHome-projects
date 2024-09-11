# ESPHome-projects
Store of my [ESPHome](https://esphome.io/) scripts and descriptions

##  [Garage door remote control](garage-door/garage-door.yaml)
This project is an [D1 Mini](https://docs.platformio.org/en/latest/boards/espressif32/wemos_d1_mini32.html) with an attached relay to control a Guardian 21230L garage door.
The relay is wired up to terminals 2 & 3 on the 21230L and act as a button press to toggle the open/close cycle of the door.
The D1 Mini is connected to the home network via WiFi and is controlled by Home Assistant via the ESPHome integration and is controled on the Home Assistant dashboard though a [tile card](garage-door/garage-door-tile.yaml).
### Limitations
This remote control lacks any state detection of the garage door.

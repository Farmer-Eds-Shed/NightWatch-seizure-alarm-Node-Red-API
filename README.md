# NightWatch-seizure-alarm-Node-Red-API

## Disclaimer: This project depends on opensource software and hardware that is at best hobbiest grade and should not be considered medical grade, it should only be used in additon to in person monitoring and absaloutley not instead of!

Node-Red / Home Assistant flows for forwarding NightWatch Seizure alarms via Device API.

#### Alerts sent to:
- Alerts sent to LG WebOS TV
- Tasmota ESP Display
- Mobile via NTFY


I've created these flows for the [Nightwatch Epilepsy Sezuire Alarm](https://nightwatchepilepsy.com/), the device gives us great peace of mind with our 5yr old daughter who is prone to nocturnal seizures. We found however a few false alarms left us confused as to why the alarm may have gone off during the night with no information from the device except the alarm ringing unless we take out the laptop and log onto the web portal, this flow sends alarts via the devices API to display on a small OLED screen the reason for the alarm eg. elevated heart rate, shaking movments etc. For the display I'm using a Heltec ESP32 with integrated OLED flashed with Tasmota Dsiplay. The flow can also be used to forward alerts to extend the range of the base unit using Home Assistant entites that utilize the notify service.

![alt text](https://github.com/Farmer-Eds-Shed/NightWatch-seizure-alarm-Node-Red-API/blob/main/IMG_20230102_121240.jpg?raw=true)

https://tasmota.github.io/docs/Displays/

https://templates.blakadder.com/heltec_wifi_kit_32.html

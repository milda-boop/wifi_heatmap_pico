# Wifi Heatmap Pico
A wifi signal strength meter designed for the raspberry pi pico using waveshare screen.

# Hardware used
- Waveshare Pico LCD 1.3
- Raspberry Pi Pico W board

# Libraries used
[Drive code](https://github.com/milda-boop/wifi_heatmap_pico/blob/main/wlan.py#L7-L346) borrowed from [Instructables](https://www.instructables.com/WS-Pico-13-IPS-LCD-240x240-Display-Workout/)

# Description
- A wifi scanner produces a list of nearby wifi networks.
- The toggle is used to move up and down the list, and to select a network.
- Upon selection, the screen changes colours between RED (weak) and YELLOW (strong) based on signal strength.


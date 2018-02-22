# Readme

This is a custom component for the media_player component of [Home Assistant][1]
It allows you to remotely control your enigma2 compatible satellite/cable receivers.
You must install OpenWebif from your enigma2 image.

Tested with OpenWebiv versions:
  - 0.2.7
  - 1.3.0
  
What is working:
    - Power status: on, off
    - Loads all sources from first bouquet. (Current channel and possibility to change channel)
    - Volume regulation
    

To use this custome component, place the file `enigma.py` inside your folder `~/custom_components/media_player` which is inside your Home Assistant configuration directory.

[1]: https://home-assistant.io


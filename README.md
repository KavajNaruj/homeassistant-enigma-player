# Readme

This is a custom component for the media_player component of [Home Assistant][1]
It allows you to remotely control your enigma2 compatible satellite/cable receivers.
You must install OpenWebif from your enigma2 image.

  
What is working:
    - Power status: on, off, standby
    - Loads all sources from first bouquet. (Current channel and possibility to change channels)
    - Volume regulation (mute, set, step)
    - Change channel (Selecting from source list or via Right/Left - from remote controller)
    - Current channel and current event
    - Picon from current channel
    - Supports authentication and multiple receivers
    
Tested with OpenWebif versions:
  - 0.2.7
  - 1.3.0

To use this customem component, place the file `enigma.py` inside your folder `~/custom_components/media_player` which is inside your Home Assistant configuration directory.

joao.amaro@gmail.com

[1]: https://home-assistant.io


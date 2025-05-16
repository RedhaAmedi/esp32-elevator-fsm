# ESP32 Elevator Controller - Finite State Machine

A fun project where I built an elevator controller on the ESP32 using a finite state machine (FSM) with function pointers in C. The elevator moves between three floors using LEDs, and a push button simulates passenger requests.

## Features
- Three LEDs show elevator position (Upper, Middle, Lower)
- Button press cycles through travel requests
- Elevator moves with delays for travel and boarding
- Requests are queued and served in order

## Hardware
- ESP32 (NodeMCU-32S)
- 3 LEDs and 1 push button on a breadboard

## Software
- PlatformIO + VSCode
- ESP-IDF framework
- C programming (FSM with function pointers)

## Demo Video  
https://youtu.be/_mxtrbVrhvQ

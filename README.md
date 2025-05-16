# 🌿 ESP32 Elevator Controller - Finite State Machine 🌿

A little fun project where I built an elevator controller on the ESP32 using a finite state machine (FSM) with function pointers in C. The elevator travels between three floors, shown by LEDs, and a push button acts like a traveler calling the lift.

## ✨ Features
- Three LEDs light up to show the elevator’s current floor (Upper, Middle, Lower)
- Push the button to call the elevator for new travel requests
- Elevator moves smoothly with small pauses for travel and boarding
- Requests wait their turn and get served one by one

## 🛠️ Hardware
- ESP32 (NodeMCU-32S)
- 3 LEDs + 1 push button on a breadboard

## 💻 Software
- PlatformIO & VSCode
- ESP-IDF framework
- C programming (FSM with function pointers)

## 🎥 Demo Video  
[![Watch the elevator in action](https://img.youtube.com/vi/_mxtrbVrhvQ/hqdefault.jpg)](https://youtube.com/shorts/_mxtrbVrhvQ)


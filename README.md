# Gesture-Controlled Bluetooth Speaker

![enter image description here](https://raw.githubusercontent.com/EmilWijayasekara/gesture-controlled-bluetooth-speaker/main/assets/projectGCBS.jpg)

Welcome to the Gesture-Controlled Bluetooth Speaker project! This project combines the power of computer vision, machine learning, and embedded systems to create a Bluetooth speaker that can be controlled using hand gestures.

## Introduction

This project aims to develop a Bluetooth speaker that can be controlled using hand gestures. It leverages the capabilities of an ESP32-CAM module for capturing images and Edge Impulse for gesture recognition. The recognized gestures are then used to control the playback of music on the Bluetooth speaker.

![enter image description here](https://raw.githubusercontent.com/EmilWijayasekara/gesture-controlled-bluetooth-speaker/main/assets/photo-collage.png.png)

## Features

-   **Gesture Recognition**: Uses machine learning to recognize hand gestures.
-   **Bluetooth Connectivity**: Connects to Bluetooth-enabled devices for audio playback.
-   **Real-Time Control**: Provides real-time control over the speaker using gestures.

## Hardware Requirements

-   ESP32-CAM module
-   AI-Thinker camera module
-   Bluetooth speaker
-   Breadboard and jumper wires
-   Power supply

## Software Requirements

-   Arduino IDE
-   Edge Impulse (Web Service)
-   ESP32 Board Manager for Arduino
-   Necessary Arduino libraries:
    -   `esp_camera`
    -   `ArduinoJson`

![enter image description here](https://raw.githubusercontent.com/EmilWijayasekara/gesture-controlled-bluetooth-speaker/main/assets/model1.png)

![enter image description here](https://raw.githubusercontent.com/EmilWijayasekara/gesture-controlled-bluetooth-speaker/main/assets/classification1.png)

## Usage

1.  Power on your ESP32-CAM module.
2.  Pair your Bluetooth speaker with your device.
3.  Use the recognized gestures to control the playback on the Bluetooth speaker:
    -   **Play/Pause**: Gesture 1
    -   **Next Track**: Gesture 2
    -   **Previous Track**: Gesture 3
    -   **Volume Up**: Gesture 4 (yet to implement)
    -   **Volume Down**: Gesture 5 (yet to implement)

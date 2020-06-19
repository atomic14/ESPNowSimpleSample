# Introduction

This project demonstrates how to use ESP-NOW to send messages to other ESP devices without using WiFi.

You can find an overview of ESP-NOW [here](https://www.espressif.com/en/products/software/esp-now/overview).

And detailed documentation [here](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_now.html).

[![Demo Video](https://img.youtube.com/vi/GLoXRyAtytY/0.jpg)](https://www.youtube.com/watch?v=GLoXRyAtytY)

The code has been written using platform.ide, but you it will work equally well in the Arduino IDE.

# Setup

For the broadcast example just push the sketch to a couple of ESP32 devices. You should see that pushing the "boot" button on one of the devices turns the LED on and off on both devices.

To set up peer-to-peer communication make a not of the MAC address of one of the devices and use that instead of the broadcast address.

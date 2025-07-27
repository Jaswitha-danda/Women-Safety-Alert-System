# Women-Safety-Alert-System
An IoT-based safety system to help women in distress by sending alert messages to authorities,activating a buzzer,and blinking street lights.

#Table of contents 
-[overview](#overview)
-[Features](#features)
-[components used](#components-used)
-[software used](#software-used)
-[circuit Diagram](#circuit-diagram)
-[working](#working)
-[How to use](#how to use)
-[Output](#output)
-[Future Scope](#future-scope)

---

## Overview

This project aims to improve women's safety in public areas. A button on the street pole can be pressed when a woman feels unsafe. It triggers a buzzer and blinking lights and sends an alert message to nearby authorities using a Wi-Fi module with the location and street number.

---

## Features

- One-touch emergency button
- Sends alert message using Wi-Fi (ESP8266)
- Buzzer activation
- Blinking LED to attract attention
- Monitors data on ThingView/ThingSpeak 

---
## Components Used

- ESP8266 
- Push Button
- Buzzer
- White LED 
- Breadboard
- Jumper Wires
- Power Source

---

##  Software Used

- Arduino IDE
- ThingSpeak / ThingView

---

##  Circuit Diagram

![WhatsApp Image 2025-07-27 at 12 05 15_6e238062](https://github.com/user-attachments/assets/6ef548d2-b271-4a6a-ad33-cd4ed54b5c72)


##  Working

1. When the button is pressed, the ESP8266 connects to Wi-Fi.
2. Sends an alert message with street number to ThingSpeak/ThingView.
3. Buzzer starts ringing.
4. LED starts blinking.
5. The streetlight color is changed to alert others.
6. Authorities get notified in real-time.

---




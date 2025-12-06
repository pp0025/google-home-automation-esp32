# 🏠✨ **Google Home Automation using ESP32**

### *Voice-Controlled Smart Home System using Arduino IoT Cloud & Google Assistant*

<p align="center">
  <img src="images/google-home-automation.jpg" width="420px" />
</p>

---

## 🚀 **Overview**

This project implements a fully functional **voice-controlled home automation system** using an **ESP32**, **relay drivers**, **Arduino IoT Cloud**, and **Google Assistant**.

Users can control lights, fans, and appliances hands-free using **Google Home voice commands** — with real-time cloud synchronization and remote monitoring.

---

## ⚙️ **Tech Stack**

| Category            | Tools/Hardware                 |
| ------------------- | ------------------------------ |
| **Microcontroller** | ESP32 Dev Module               |
| **Cloud Platform**  | Arduino IoT Cloud              |
| **Voice Assistant** | Google Assistant / Google Home |
| **Communication**   | Wi-Fi (MQTT/WebSockets)        |
| **Hardware**        | Relay Module, Power Supply     |
| **IDE**             | Arduino IDE                    |

---

## ⭐ **Features**

✔ Voice-controlled appliance switching
✔ Remote access via Arduino IoT Cloud
✔ Real-time device state updates
✔ Google Assistant voice routines
✔ Secure cloud communication
✔ Expandable to multiple devices

---

## 🔧 **Hardware Components**

* ESP32 Development Board
* 1/2/4-Channel Relay Module
* Household appliances (bulb, fan, etc.)
* Power supply module
* Jumper wires

---

## 💡 **How It Works**

1. ESP32 connects to **Arduino IoT Cloud**
2. Google Assistant triggers cloud variables using linked accounts
3. Cloud updates are pushed instantly to the ESP32
4. ESP32 toggles relay switches accordingly
5. Appliance reacts in real-time

It's fast. It's reliable. It's fully automated.

---

## 🔌 **Circuit Wiring**

Upload diagram in:
`/circuit-diagrams/wiring-diagram.png`

**Basic Relay Wiring:**

```
ESP32 GPIO → Relay IN Pins  
5V → Relay VCC  
GND → Relay GND (Shared with ESP32)
NO/COM → Appliance Line Cut
```

---

## 🗣️ **Google Assistant Setup**

1. Create Arduino IoT Thing → Add variables
2. Sync with Google Home via **Linked Services**
3. Create commands like:

   * “Hey Google, turn on the bedroom light”
   * “Hey Google, switch off the fan”

Add screenshots to:
`/images/google-home-dashboard.jpg`

---

## 💻 **Source Code**

Main file:

```
/src/main.ino
```

### 🔧 Core Functionalities:

* Cloud variable sync
* Relay switching logic
* Wi-Fi connection handler
* State monitoring

---


---

## 📁 **Project Folder Structure**

```
google-home-automation-esp32/
│
├── src/
│   └── main.ino
│
├── circuit-diagrams/
│   └── wiring-diagram.png
│
├── images/
│   ├── google-home-dashboard.jpg
│   ├── relay-setup.jpg
│   └── device-connection.jpg
│
└── README.md
```

---

## 📚 **Libraries Used**

```text
ArduinoIoTCloud.h
Arduino_ConnectionHandler.h
WiFi.h
```

---

## 🔮 **Future Improvements**

* Add dimming controls
* Add scheduling (timed automation)
* Add appliance energy monitoring
* Add motion sensor triggers

---

## ❤️ **Developed By**

**Akash Roy**
Embedded & IoT Developer
📧 [aroy50809@gmail.com](mailto:aroy50809@gmail.com)

---

## ⭐ **Support**

If you like this project, please ⭐ **star the repository** — it keeps the motivation high!

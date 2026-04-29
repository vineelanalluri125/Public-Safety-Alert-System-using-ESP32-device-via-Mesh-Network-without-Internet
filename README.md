
## 📡 Public Safety Alert System using ESP32 Mesh Network (No Internet Required)

This project presents a **decentralized Public Safety Alert System** built using ESP32 devices that communicate over a **mesh network**, enabling real-time emergency alerts **without relying on the internet or mobile networks**.

### 🚀 Overview

In critical situations such as natural disasters, industrial hazards, or remote area emergencies, traditional communication systems often fail due to network outages or infrastructure damage. This system addresses that problem by using **ESP32-based mesh networking**, where each node can send, receive, and forward messages across the network.

The result is a **self-healing, scalable, and resilient communication system** capable of delivering emergency alerts even in complete network failure scenarios.



### ⚙️ Key Features

* 📶 **Internet-Free Communication** – Works without Wi-Fi, cellular, or central servers
* 🔁 **Mesh Networking (Multi-hop)** – Messages propagate across nodes seamlessly
* ⚡ **Real-Time Alerts** – Instant notification across all connected devices
* 🔒 **Secure Messaging** – Authenticated packets prevent false alerts
* 🔔 **Multi-Modal Alerts** – LEDs, buzzers, and optional mobile notifications
* 🧠 **Smart Triggering** – Alerts can be triggered manually or via sensors
* 📈 **Scalable Architecture** – Easily expandable by adding more ESP32 nodes
* 🔋 **Low Power & Cost Effective** – Suitable for battery/solar-powered setups



### 🏗️ System Architecture

* Each ESP32 acts as an independent **mesh node**
* Nodes communicate using **ESP-MESH / ESP-NOW protocols**
* Alerts are transmitted using **multi-hop routing**
* Includes:

  * **TTL (Time-To-Live)** to prevent infinite looping
  * **Duplicate suppression** to avoid message flooding
* Optional **gateway node** for cloud integration and monitoring


### 🔧 Hardware Components

* ESP32 Development Boards
* Push Buttons (manual alert trigger)
* Buzzers & LEDs (alert indicators)
* LCD/OLED Display (optional)
* Sensors (smoke, gas, temperature – optional)
* Power Supply / Battery
* GPS Module (optional for location tracking)



### 💻 Software & Technologies

* Arduino IDE / ESP-IDF
* C/C++ Programming
* ESP-MESH / ESP-NOW Protocols
* MQTT (optional for gateway communication)
* Cryptographic libraries for secure messaging



### 📡 Working Principle

1. An alert is triggered manually or via sensors
2. The node creates a **lightweight alert packet** (type, ID, timestamp)
3. Message is broadcast to nearby nodes
4. Each node forwards it across the mesh (**multi-hop**)
5. Receiving nodes activate:

   * 🔴 LEDs
   * 🔊 Buzzers
   * 📱 Optional notifications
6. Optional gateway sends data to cloud/dashboard



### 🌍 Applications

* Disaster Management (floods, earthquakes, wildfires)
* Rural & Remote Communication
* Industrial Safety Systems
* Public Event Safety
* Military & Defense Communication
* Emergency Evacuation Systems



### ✅ Advantages

* Works during complete network failure
* No single point of failure (decentralized)
* Fast and reliable communication
* Low deployment cost
* Easy to scale and maintain
* Energy-efficient design



### 🔮 Future Scope

* Integration with advanced sensors for automated alerts
* Mobile app / web dashboard for monitoring
* Cloud integration (AWS IoT, Firebase, etc.)
* Enhanced security with TLS/SSL encryption
* AI-based alert prioritization and analytics



### 📌 Conclusion

This project demonstrates a **robust, low-cost, and reliable emergency communication system** using ESP32 mesh networking. By eliminating dependency on traditional infrastructure, it ensures that **critical alerts are delivered quickly and reliably when they are needed most**.





# IOT-MQTT-Web-Dashboards
In this repository, I plan to provide real time smart web dashboards that work with the MQTT protocol. They will be available both as open source code for development and as quick access instances hosted on my servers, so you can more easily test and deploy your own projects.

-  **🌐Global Control** from anywhere.
-  **💻Web Dashboards** For applied projects. 
-  **⛓️‍💥Used Free Public MQTT Broker** for connection.
-  **⚙️Expandable** for commercial projects.
## Connection solution
For these projects, the mqtt protocol is used for connection. I have previously published information about the free mqtt broker on my personal site.[MQTT broker](https://masihch.com/mqtt-public-broker-free-test-server/)
## 1.Basic Control
A simple graphical dashboard that connects to an MQTT broker and sends ON/OFF messages to a topic. The device on the other side reacts by changing the state of a GPIO pin.

- ESP32
- Host(For personal startup)
- MQTT Broker(For personal startup)
- You can read about my free MQTT broker here:[My Broker](https://masihch.com/mqtt-public-broker-free-test-server/)

## 🚀 How to Run

First, clone the repository:

```bash
git clone https://github.com/masihch/esp32-led-anywhere-control.git
cd esp32-led-anywhere-control

```
-Then,Open the program in the ESP32 folder and upload it to the esp32
-Open this URL and start controlling! [Dahboard](https://lab.masihch.com/control-esp32-from-anywhere-in-the-world/index.html)
## View of the project
![ESP32-Dash](https://github.com/masihch/iot-mqtt-web-dashboards/blob/main/images/view.webp)
![Dashboard-control](https://github.com/masihch/iot-mqtt-web-dashboards/blob/main/images/web-dashboard.webp)
![Dashboard-monitoring](https://github.com/masihch/iot-mqtt-web-dashboards/blob/main/images/web-monitor-dashboard.webp)

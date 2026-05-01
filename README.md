[![Github issues](https://img.shields.io/github/issues/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/issues)
[![Github forks](https://img.shields.io/github/forks/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/network/members)
[![Github stars](https://img.shields.io/github/stars/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/stargazers)
[![Top language](https://img.shields.io/github/languages/top/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)

---

## 🧠 Tags

`ESP32` `IoT` `WiFi Hacking` `Deauthentication` `Captive Portal` `Microcontroller Security` `Arduino`

---

---

# 🚨 ESP32 Evil Twin WiFi Hacking | Deauthentication & Captive Portal 🚨

> **Disclaimer:** This project is for **educational purposes only**. Use it responsibly and legally. Unauthorized attacks on networks are illegal in most countries. 🌐🔒

---

![Profile Views](https://komarev.com/ghpvc/?username=aadesh0706&color=blue)  
*Active since*: `September 2024`

**Account From:** `September 2020`

---

### 🎥 **Demo Video**

Check out the demo of this project in action! 🎬  
[![ESP32 Evil Twin WiFi Hacking](https://img.youtube.com/vi/AEb33trYEAY/0.jpg)](https://www.youtube.com/shorts/AEb33trYEAY)  
Click the thumbnail or follow [this link](https://www.youtube.com/shorts/AEb33trYEAY) to watch.

---

### 🎯 **Project Overview**

This repository demonstrates how to execute an **Evil Twin WiFi Hacking** attack using an **ESP32** module. The attack forces users off their legitimate network by sending **deauthentication packets** and lures them into connecting to a fake access point where a **captive portal** captures their WiFi credentials. 

The project leverages **HTML**, **CSS**, and **JavaScript** to build a custom front-end for the captive portal, making it look like a legitimate login page.

---

## 🚀 **Features**
- 🛑 **Deauthentication Attack**: Disconnects devices from their current WiFi network.
- 🌐 **Captive Portal**: A fake login page where users unknowingly enter their WiFi credentials.
- 🎨 **Custom Frontend**: Built using **HTML**, **CSS**, and **JavaScript** for user interaction.
- 📡 **ESP32 Integration**: WiFi hacking on a powerful yet affordable ESP32 module.

---

## 🛠️ **Setup and Installation**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal.git
cd IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal
```

### 2️⃣ **Install Required Libraries**

Make sure you have the necessary libraries and tools installed to program the ESP32:

- **ESP32 Core for Arduino**: [Install Guide](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

### 3️⃣ **Upload the Code to ESP32**
1. Open the `esp32_deauth_attack.ino` file in your Arduino IDE.
2. Connect your ESP32 to your computer via USB.
3. Select your ESP32 board from the Tools > Board menu.
4. Click **Upload**.

### 4️⃣ **Customize the Captive Portal**
- The captive portal files are located in the `html/` folder. 🎨
- You can easily edit the design using **HTML**, **CSS**, and **JavaScript** to match your desired look and feel.

---

## ⚡ **How to Run the Attack**

1. **Launch the Deauthentication Attack**: 📶 Force devices off the legitimate WiFi network.
2. **Start the Fake AP**: 🖧 Broadcast your rogue access point.
3. **Use the Captive Portal**: 🌐 When users attempt to reconnect, they are directed to a fake login page.
4. **Capture WiFi Credentials**: 🔐 Credentials entered by users are logged on the ESP32.

---

## 📂 **Files Included**
- `esp32_deauth_attack.ino`: The main code for the deauthentication attack.
- `html/`: Contains all the files for the captive portal (HTML, CSS, JavaScript).
- `README.md`: Overview, setup instructions, and usage information.

---

## 🔗 **How It Works**

1. **Deauthentication Attack**: The ESP32 sends deauth packets to disconnect devices from their original network.
2. **Rogue Access Point**: After being disconnected, the ESP32 broadcasts a rogue AP with a similar name (SSID) to the legitimate one.
3. **Captive Portal**: When users attempt to connect to the rogue AP, they are redirected to a fake login page asking for WiFi credentials.
4. **Credentials Logged**: Any credentials entered are captured and stored on the ESP32.

---

## 💻 **Technologies Used**
- **ESP32**: Low-cost WiFi module.
- **HTML**: Structure for the captive portal.
- **CSS**: Styling for a user-friendly portal interface.
- **JavaScript**: Handles user interactions and form submissions.

---

## 🚧 **Future Improvements**
- 🔒 Add encryption to securely transmit credentials.
- 📊 Create a log file to store captured credentials.
- 🔧 Improve the accuracy of deauthentication attacks.

---

## 👨‍💻 **Contributing**

Want to improve this project? Feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome! 🛠️

---

## 📝 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 📜

---

## ⚠️ **Disclaimer**

This project is intended for **educational and ethical testing purposes** only. **Do not** use this code to target any WiFi network without explicit permission from the network owner. Always comply with local laws and regulations.

---

### 📦 **Repository Tags**
```
ESP32, Evil Twin, WiFi Hacking, Deauthentication, Captive Portal, HTML, CSS, JavaScript, Cybersecurity, Ethical Hacking, ESP32 WiFi, IoT, WiFi Pentesting

`NOTES FOR CSN150``
# YOUR_NAME:Zainab Choudhury


## Equipment Used
- ESP32-CAM / ESP32 development board
- USB cable or USB-to-serial adapter
- Computer with Arduino IDE
- Phone or laptop for testing the Wi-Fi connection
- GitHub account for submitting the forked project

## Tools Used
- Arduino IDE
- ESP32 board package by Espressif Systems
- Serial Monitor
- GitHub
- Web browser
- ChatGPT for documentation help

## Steps I Followed
1. I forked the assigned GitHub repository.
2. I opened Arduino IDE and ensured it was connected to AI Thinker ESP32-CAM on COM6 (my ESP32-CAM connection).
3. I created a new Arduino sketch.
4. I pasted the ESP32 captive portal code into the sketch.
this is the code.
#include <WiFi.h>
#include <WebServer.h>
#include <DNSServer.h>

const byte DNS_PORT = 53;

IPAddress apIP(192, 168, 4, 1);
DNSServer dnsServer;
WebServer server(80);

const char* ssid = "CSN150-Lab-Demo";
const char* password = "classdemo123";

String portalPage() {
  return R"rawliteral(
<!DOCTYPE html>
<html>
<head>
  <title>CSN150 ESP32 Captive Portal Demo</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 30px;
    }
    .card {
      background: white;
      max-width: 700px;
      margin: auto;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(0,0,0,0.15);
    }
    h1 {
      color: #222;
    }
    .safe {
      color: green;
      font-weight: bold;
    }
    .warning {
      background: #fff3cd;
      padding: 12px;
      border-radius: 8px;
      margin-top: 15px;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>CSN150 ESP32 Captive Portal Demo</h1>
    <p class="safe">Authorized classroom lab demonstration.</p>

    <p>This ESP32 is running its own Wi-Fi access point and captive portal.</p>

    <p>This project demonstrates how captive portals can redirect users after they connect to a Wi-Fi network.</p>

    <div class="warning">
      <strong>Safety Note:</strong>
      This demo does not impersonate a real router, collect credentials, intercept traffic, or attack users.
    </div>

    <h2>Project Status</h2>
    <p>The ESP32 access point and captive portal are working correctly.</p>

    <h2>Network Information</h2>
    <p><strong>SSID:</strong> CSN150-Lab-Demo</p>
    <p><strong>Portal Address:</strong> http://192.168.4.1</p>
  </div>
</body>
</html>
)rawliteral";
}

void handleRoot() {
  server.send(200, "text/html", portalPage());
}

void handleCaptivePortal() {
  server.send(200, "text/html", portalPage());
}

void handleNotFound() {
  server.sendHeader("Location", "http://192.168.4.1", true);
  server.send(302, "text/plain", "");
}

void setup() {
  Serial.begin(115200);
  delay(1000);

  WiFi.mode(WIFI_AP);

  WiFi.softAPConfig(apIP, apIP, IPAddress(255, 255, 255, 0));
  WiFi.softAP(ssid, password);

  dnsServer.start(DNS_PORT, "*", apIP);

  server.on("/", handleRoot);

  // Common captive portal detection URLs
  server.on("/generate_204", handleCaptivePortal);        // Android
  server.on("/gen_204", handleCaptivePortal);             // Android
  server.on("/hotspot-detect.html", handleCaptivePortal); // Apple
  server.on("/library/test/success.html", handleCaptivePortal); // Apple
  server.on("/ncsi.txt", handleCaptivePortal);            // Windows
  server.on("/connecttest.txt", handleCaptivePortal);     // Windows
  server.on("/fwlink", handleCaptivePortal);              // Windows

  server.onNotFound(handleNotFound);

  server.begin();

  Serial.println();
  Serial.println("=================================");
  Serial.println("CSN150 ESP32 Captive Portal Demo");
  Serial.println("=================================");
  Serial.print("Wi-Fi Name: ");
  Serial.println(ssid);
  Serial.print("Wi-Fi Password: ");
  Serial.println(password);
  Serial.print("Portal URL: http://");
  Serial.println(apIP);
  Serial.println("Connect a phone or laptop to the Wi-Fi network.");
  Serial.println("Then open http://192.168.4.1");
}

void loop() {
  dnsServer.processNextRequest();
  server.handleClient();
}
5. I verified the code using Sketch → Verify/Compile.
6. I uploaded the code using Sketch → Upload.
7. I opened Serial Monitor and confirmed the ESP32 started correctly.
8. I connected my laptop to the Wi-Fi network named CSN150-Lab-Demo.
9. It directly opened http://192.168.4.1 in a browser.
10. I confirmed that the captive portal page loaded successfully.
11. I took screenshots showing the working project.

## Problems / Solutions
No problems occurred during the setup and testing process. Everything worked as expected.

## Final Report
For this assignment, I set up an ESP32 to create its own Wi-Fi network and host a simple captive portal page. After uploading the code, I was able to connect to the network from my laptop and access the webpage without any issues.

T

---


# **✨Smart Disposable Bin**

---

##  **About the Project**

**Smart Disposable Bin** is an **IoT-based automatic waste management system** that helps in hygienic and efficient waste segregation.

It works automatically by detecting waste, opening the lid without contact, identifying the type of waste, and monitoring how full the bin is.

All this information is sent to the cloud and displayed in real time through a web dashboard.


---

## ⚙️ **Working of the Project**

1. **Lid Automation:**
   
   An **IR sensor** detects when a person approaches the bin, and a **servo motor** automatically opens the lid. It closes after a few seconds.

2. **Waste Classification:**
   
   An **RFID reader** identifies whether the waste is biodegradable, non-biodegradable, or metallic using assigned RFID tags.

3. **Fill Level Monitoring:**
   
   **Ultrasonic sensors** measure how full the bin is and calculate the percentage of waste inside.

4. **Cloud Connectivity:**
   
   The collected data is sent to the **ThingSpeak IoT platform**, where it can be viewed online.

5. **Web Dashboard:**
    
   A simple **HTML and JavaScript web page** displays live data from ThingSpeak, showing the status of organic and inorganic bins.

---



## 🔩 **Hardware Used**

| **Component** | **Purpose** |
|----------------|-------------|
| **ESP32 / NodeMCU** | Main microcontroller with Wi-Fi |
| **IR Sensor** | Detects nearby motion to open the lid |
| **Servo Motor** | Controls automatic lid movement |
| **RFID Reader (MFRC522)** | Detects type of waste |
| **RFID Tags** | Attached to waste for classification |
| **Ultrasonic Sensor (HC-SR04)** | Measures bin fill level |
| **Power Supply** | Provides power to all components |

---

## 💻 **Software Used**

| **Software / Platform** | **Purpose** |
|--------------------------|-------------|
| **Arduino IDE** | Programming and uploading code to ESP32 |
| **ThingSpeak** | Cloud platform for data storage and visualization |
| **HTML, CSS, JavaScript** | Web dashboard for real-time monitoring |
| **VS Code ** | Code editing and documentation |

---

## ⚙️ Prototype Connection Setup
        <img width="847" height="515" alt="prototype connection setup" src="https://github.com/user-attachments/assets/831bd350-ca6c-4ce8-8e49-1f23969e7b5d" />






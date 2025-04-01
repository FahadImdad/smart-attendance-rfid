## 📌 **Smart Attendance System Using RFID**  

![Project Poster](attendance_poster.png)  

### 🔹 **Overview**  
The **Smart Attendance System Using RFID** is an innovative solution that automates attendance management in educational institutions and workplaces. The system utilizes **RFID technology** to accurately and securely record attendance, preventing proxy attendance and reducing administrative workload.  

---

## 🎥 **Demo Video**  
[![Watch the Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)  

_(Replace `YOUR_VIDEO_ID` with your actual YouTube video ID.)_  

---

## 🛠 **Hardware Requirements**  
- 🖥 **Raspberry Pi 4B**  
- 📶 **RFID-RC522 Module**  
- 📟 **0.96” OLED Display**  
- 🔌 **ADS1115 Analog-to-Digital Converter**  
- 🔧 **Jumper Wires & Breadboard**  

---

## 🔧 **Circuit Diagram**  
![Circuit Diagram](image.png)  

---

## ⚙️ **Installation & Setup**  

### 📥 **1. Clone the Repository**  
```sh
git clone https://github.com/your-username/smart-attendance-system-rfid.git
cd smart-attendance-system-rfid
```

### 🛠 **2. Install Dependencies**  
Ensure your Raspberry Pi has the required libraries:  
```sh
sudo apt update && sudo apt upgrade -y
sudo apt install python3-pip
pip3 install RPi.GPIO spidev adafruit-circuitpython-ssd1306
```

### 🚀 **3. Run the System**  
```sh
python3 main.py
```

---

## 📌 **Features**  
✅ **Automated Attendance Marking** – RFID-based scanning for quick check-ins.  
✅ **Secure & Accurate** – Eliminates manual errors and prevents proxy attendance.  
✅ **Real-Time Monitoring** – Integrates with a database for instant attendance tracking.  
✅ **OLED Display Support** – Shows scanned user details on a mini display.  
✅ **Data Logging & Analytics** – Generates reports for attendance trends.  

---

## 📜 **License**  
This project is **open-source** under the **MIT License**. Feel free to use and modify it!  

📢 **Contributions are welcome!** Create a pull request if you'd like to improve this project.  


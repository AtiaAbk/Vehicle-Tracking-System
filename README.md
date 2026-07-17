# 🚦 Traffic Tracker – Real-Time Vehicle Detection & Counting

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-red?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Firebase](https://img.shields.io/badge/Firebase-Cloud%20Database-orange?style=for-the-badge&logo=firebase)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

### 🚗 AI-Powered Real-Time Traffic Monitoring System

*Detect • Track • Count • Analyze*

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Project Structure](#-project-structure)
- [Installation](#️-installation)
- [Usage](#-usage)
- [Output](#-output)
- [Technology Stack](#️-technology-stack)
- [Future Improvements](#-future-improvements)
- [Applications](#-applications)
- [Sample Detection](#-sample-detection)
- [Contributing](#-contributing)
- [Author](#-author)
- [Acknowledgments](#-acknowledgments)
- [Support](#-support)
- [License](#-license)

---

## 📖 Overview

**Traffic Tracker** is an intelligent traffic monitoring system powered by **YOLOv8**, **OpenCV**, and **Firebase**. It performs **real-time vehicle detection, tracking, and counting** while sending live analytics to the cloud.

Designed for **smart city applications**, **traffic management**, **parking systems**, **road analytics**, and **research**, the project delivers accurate vehicle statistics with an intuitive visual interface.

---

## ✨ Features

✅ **Real-Time Vehicle Detection**
- Detects cars, buses, trucks, motorcycles, and other vehicles using **YOLOv8**.

✅ **Multi-Class Vehicle Counting**
- Counts each vehicle category independently.
- Supports **Entry** and **Exit** counting.

✅ **Object Tracking**
- Persistent tracking minimizes duplicate counts.
- Stable IDs for moving vehicles.

✅ **Firebase Integration**
- Uploads traffic statistics directly to **Firebase Realtime Database**.
- Ideal for dashboards and remote monitoring.

✅ **Live Analytics Overlay**
- Bounding boxes
- Vehicle labels
- Entry/Exit counters
- Real-time statistics

✅ **Flexible Input**
- Webcam
- CCTV
- IP Camera
- Recorded video files

---

## 🎥 Demo

<p align="center">
<img src="demo-demo.gif" width="850">
</p>

---

## 📂 Project Structure

```
traffic-tracker/
│
├── traffic_tracker.py
├── tracker.py
├── serviceAccountKey.json
├── yolov8s.pt
├── demo-demo.gif
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/masumb2k2/traffic-tracker.git

cd traffic-tracker
```

### 2️⃣ Install Dependencies

```bash
pip install ultralytics
pip install opencv-python
pip install pandas
pip install firebase_admin
pip install cvzone
```

Or simply:

```bash
pip install -r requirements.txt
```

### 3️⃣ Download YOLOv8 Model

Download `yolov8s.pt` from Ultralytics and place it inside the project directory.

### 4️⃣ Configure Firebase

1. Create a Firebase project.
2. Download `serviceAccountKey.json` from your Firebase project settings.
3. Place it inside the project folder.
4. Update the database URL inside the source code.

> ⚠️ **Note:** Never commit `serviceAccountKey.json` to a public repository. Add it to your `.gitignore` to keep your credentials safe.

---

## 🚀 Usage

### Process a Video

```bash
python traffic_tracker.py --video tf.mp4
```

### Use Webcam

```bash
python traffic_tracker.py --cam 0
```

### IP Camera (Optional)

```bash
python traffic_tracker.py --cam http://YOUR_CAMERA_IP
```

---

## 📊 Output

The application provides:

- 🚗 Vehicle Detection
- 📍 Object Tracking
- 📈 Entry Counter
- 📉 Exit Counter
- 🏍️ Vehicle Classification
- ☁️ Live Firebase Updates
- 📺 Real-Time Video Visualization

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Programming |
| YOLOv8 | Object Detection |
| OpenCV | Computer Vision |
| Firebase RTDB | Cloud Storage |
| Pandas | Data Processing |
| cvzone | Visualization |
| Custom Tracker | Multi-Object Tracking |

---

## 📈 Future Improvements

- [ ] Speed Estimation
- [ ] Vehicle Number Plate Recognition (ANPR)
- [ ] Traffic Density Analysis
- [ ] Automatic Violation Detection
- [ ] Heatmap Generation
- [ ] Web Dashboard
- [ ] Email/SMS Alerts
- [ ] Multi-Camera Support

---

## 🌍 Applications

- 🚦 Smart Traffic Management
- 🏙️ Smart Cities
- 🚔 Traffic Law Enforcement
- 🅿️ Parking Analytics
- 📊 Traffic Research
- 🚛 Logistics Monitoring
- 🛣️ Highway Surveillance

---

## 📸 Sample Detection

| Detection | Tracking | Counting |
|-----------|----------|----------|
| ✅ Cars | ✅ IDs | ✅ Entry |
| ✅ Bus | ✅ Persistent | ✅ Exit |
| ✅ Truck | ✅ Accurate | ✅ Live |
| ✅ Motorcycle | ✅ Robust | ✅ Firebase |

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added awesome feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request 🎉

---

## 👨‍💻 Author

### **Atia Sanjida**

Information & Communication Engineering (ICE) Student
Bangladesh Army University of Engineering & Technology (BAUET)

💙 Passionate about:
- Artificial Intelligence
- Computer Vision
- Cyber Security
- Machine Learning
- Embedded Systems

GitHub: [https://github.com/AtiaAbk](https://github.com/AtiaAbk)

---

## 🙏 Acknowledgments

Special thanks to **Masum Billah** for his valuable guidance and advisory support throughout the development of this project. His mentorship and insights were instrumental in shaping the direction and quality of Traffic Tracker.

---

## ⭐ Support

If this project helped you, consider giving it a **⭐ Star** on GitHub.

It motivates future development and helps others discover the project.

---

## 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute it in accordance with the license.

---

<div align="center">

### 🚀 Building Smarter Roads with Artificial Intelligence

**Detect • Track • Count • Analyze**

#Author 
**Atia Sanjida**
*Advised by Masum Billah*

</div>

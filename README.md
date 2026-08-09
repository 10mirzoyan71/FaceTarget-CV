# 🎯 Real-Time Forehead Micro-Target Tracking System

A lightweight, real-time computer vision project built with **Python** and **OpenCV**. It detects faces from a webcam feed and locks a precise crosshair onto the user's forehead.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red?style=for-the-badge&logo=opencv&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=for-the-badge)

---

## ✨ Features
* **Real-Time Detection:** Utilizes OpenCV's Haar Cascade classifier to quickly detect frontal faces.
* **Smart Targeting:** Automatically calculates the face center and focuses precisely on the forehead (micro-target crosshair).
* **Mirror Effect:** Horizontally flips the webcam feed for a natural user experience.
* **Low Latency:** Optimized startup configuration using DirectShow (`cv2.CAP_DSHOW`) for Windows environments.

---

## 🛠️ Prerequisites & Installation

Make sure you have **Python** installed on your system. Then, install the required dependency:

```bash
pip install opencv-python

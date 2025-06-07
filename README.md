# 💤 Drowsiness Detector 😴

A real-time computer vision-based drowsiness detection system using OpenCV and dlib that alerts the user when signs of drowsiness are detected.

## 🔍 Features

- 🔹 Real-time eye aspect ratio (EAR) monitoring  
- 🔹 Audio alert when drowsiness is detected  
- 🔹 Detects blinking and prolonged eye closure  
- 🔹 Lightweight and fast using OpenCV & dlib  
- 🔹 Easy to extend for vehicle driver monitoring systems  

---

## 🛠️ Tech Stack

- Python 3.6+
- OpenCV
- dlib
- imutils
- NumPy
- playsound

---

## 🚀 How It Works

1. Detects facial landmarks using dlib's shape predictor.
2. Calculates the Eye Aspect Ratio (EAR) from the eye landmarks.
3. If the EAR drops below a threshold for a continuous number of frames, a drowsiness alert is triggered.
4. The alert sound is played using the `playsound` library.

---

# 🏍️ Bike Helmet Detection using YOLO

This project is a **real-time bike helmet detection system** built using **YOLO** and **OpenCV**.  
It detects whether a bike rider is **wearing a helmet** or **not** using images, videos, or a webcam.

---

## ⭐ Features
- Real-time helmet detection  
- Works with webcam, video, and images  
- High accuracy using YOLO  
- Bounding boxes + labels + confidence score  
- Easy to run and customize  

---

## 🧠 Tech Stack
- **Python**
- **OpenCV**
- **cvzone**
- **Ultralytics YOLO (v8/v9/v11)**
- Works on **CPU/GPU**

---

## 📁 Project Structure
```
helmet_detection_project/
│── model/ # YOLO trained model (.pt file)
│── data/ # Optional images/videos
│── main.py # Main detection script
│── requirements.txt # Dependencies
│── README.md # Documentation
```


## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
### 2️⃣ Create Virtual Environment
```
python3 -m venv helmet
source helmet/bin/activate
```
### 3️⃣ Install Dependencies
```
pip install -r requirements.txt
```
### ▶️ Running the Project
## 👉 Real-time Webcam Detection
```
python main.py
```
## 👉 Run on a Video File

Inside main.py, update:
```
cap = cv2.VideoCapture("video.mp4")
```
### 🧩 Output Information
- 🟢 Helmet Detected
- 🔴 No Helmet Detected
- Bounding box + label + confidence displayed on screen

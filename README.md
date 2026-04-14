# Automatic Helmet Detection Using CNN

## 📌 Project Overview

Automatic Helmet Detection Using CNN is a real-time computer vision project that detects whether a person is wearing a helmet or not using a Convolutional Neural Network (YOLOv5-based model).

This system can be used for:

- Traffic monitoring
- Road safety enforcement
- Smart surveillance systems

---

## 🚀 Features

- Real-time webcam detection
- Helmet / No Helmet classification
- Bounding box with confidence score
- High detection accuracy
- Easy to run and deploy

---

## 🛠 Technologies Used

- Python
- PyTorch
- OpenCV
- YOLOv5 (CNN-based object detection)

---

## 📂 Project Structure

Automatic-Helmet-Detection-Using-CNN/
│
├── detect.py
├── requirements.txt
├── helmet_head_person_s.pt
└── README.md

---

## ▶️ How to Run the Project

### 1️⃣ Clone Repository

git clone https://github.com/Srushti-dev/Automatic-Helmet-Detection-Using-CNN.git

cd Automatic-Helmet-Detection-Using-CNN

### 2️⃣ Create Virtual Environment

python -m venv venv
venv\Scripts\activate

### 3️⃣ Install Requirements

pip install -r requirements.txt

### 4️⃣ Run Detection

python detect.py --weights helmet_head_person_s.pt --source 0

---

## 📸 Output

The system opens the webcam and detects:

- Helmet
- No Helmet

---

## 📌 Future Improvements

- Web dashboard integration
- Alert system for no-helmet detection
- Data logging system
- Cloud deployment

---

## 👩‍💻 Author

Srushti More

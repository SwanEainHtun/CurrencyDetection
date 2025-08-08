# 🏦 Myanmar Banknote Detection and Classification System

## 📌 Project Overview

Banknotes are essential for everyday financial transactions, making their **accurate detection and classification** crucial for applications like **automated banking**, **vending machines**, and assistive technology for the **visually impaired**.

This project introduces a powerful **Myanmar Banknote Detection and Classification System** using the **YOLOv8 object detection model**, capable of identifying and classifying seven Myanmar banknote denominations:
**50, 100, 200, 500, 1000, 5000, and 10000 kyats.**

---

## 🎯 Objectives
- Detect the presence of Myanmar currency in real-time
- Classify banknote denomination accurately using YOLOv8
- Enable live detection via webcam, video, or uploaded image
- Provide accessible and practical application for financial and assistive tools

---

## 🧠 Model Architecture

| Task              | Model   | Performance |
|------------------|---------|-------------|
| Object Detection & Classification | YOLOv8 | mAP: 98.8%, Accuracy: 90% |

The YOLOv8 model is trained to handle:
- Occlusions
- Lighting variation
- Degraded or wrinkled notes

---

## 🗃️ Dataset

- 🔗 Sources: Publicly available images from **Kaggle** + self-collected images
- 🖼️ Data annotation: Done using **Roboflow**
- 🔀 Data split: 80% training, 10% validation, 10% test
- 👛 Classes: `50`, `100`, `200`, `500`, `1000`, `5000`, `10000` kyats

---

## ⚙️ Technologies Used

- 🧠 YOLOv8 (Ultralytics)
- 🐍 Python
- 📊 Kaggle Notebooks & Google Colab
- 📦 Roboflow (for annotation)
- 🌐 Streamlit (for UI and real-time web app)
- 🎥 OpenCV (for webcam and video processing)

---

## 🚀 How to Use

### ▶️ Streamlit Web App
- Upload an image or video, or use webcam
- The model will detect and classify any visible Myanmar banknote

### 🧪 Local Setup (Optional)
1. Clone the repository:
   ```bash
   git clone https://github.com/SwanEainHtun/CurrencyDetection.git
  

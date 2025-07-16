# 🌾 Smart Seed Classification System

A computer vision–based seed classifier designed to assist farmers, seed suppliers, and agri-tech solutions in identifying and verifying the quality of agricultural seeds. Powered by a Roboflow-trained YOLOv11 model and deployed with FastAPI, this system enables accurate, real-time classification of seeds into good, bad, and impurity classes.

---

## 🚀 Key Features

✅ Uses Roboflow-trained YOLOv11 model hosted on the cloud  
✅ Detects and classifies seeds as **Good**, **Bad**, or **Impurity**  
✅ Supports real-time predictions through FastAPI backend  
✅ Returns annotated images with bounding boxes as base64  
✅ Works with Flutter, ESP32, or other automation systems  
✅ Lightweight and fast, deployable on Render, GCP, or local edge devices  
✅ CORS-enabled for easy frontend/mobile integration  

---

## 🧠 Classes

The model is trained to detect and classify the following **11 seed classes**:

| Class Name            | Category |
|-----------------------|----------|
| Good Black Channa     | Good     |
| Good Kabuli Channa    | Good     |
| Good Rajma            | Good     |
| Good Soya             | Good     |
| Good Wheat            | Good     |
| Bad Black Channa      | Bad      |
| Bad Kabuli Channa     | Bad      |
| Bad Rajma             | Bad      |
| Bad Soya              | Bad      |
| Bad Wheat             | Bad      |
| Impurity              | Other    |

> 📈 Future versions may include disease detection, seed grade prediction, and more grain varieties.

---

## ⚙️ Quickstart Guide

### 1. 📦 Install Dependencies

```bash
pip install -r requirements.txt

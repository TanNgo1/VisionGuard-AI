# 👁️ VisionGuard-AI

[![Computer Vision](https://img.shields.io/badge/AI-Computer%20Vision-orange.svg)](https://github.com/TanNgo1/VisionGuard-AI)

An advanced real-time object detection and tracking pipeline designed for security and analysis. Powered by the latest **YOLO** architecture.

## 🔥 Key Highlights
- **Real-time Processing:** Optimized for high-FPS inference.
- **Multi-Object Tracking:** Seamlessly track objects across frames.
- **Customizable:** Simple API to add custom detection classes.

## 📦 Installation
```bash
git clone https://github.com/TanNgo1/VisionGuard-AI.git
pip install ultralytics opencv-python
```

## 🖥️ Usage
```python
from ultralytics import YOLO
model = YOLO('yolo11n.pt')
results = model.predict(source='0', show=True)
```

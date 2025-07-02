# 🧠 Brain Tumor Detection using CNN with Grad-CAM GUI

This project is an AI-based medical image classification system that detects four types of brain tumors from MRI images using a custom-built Convolutional Neural Network (CNN). The system features a fully functional graphical user interface (GUI) built with **Tkinter** and includes **Grad-CAM heatmap visualizations**, detailed disease explanations, and **downloadable PDF medical reports**.

---

## 🚀 Features

✅ Detects:
- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor (Normal)**

✅ Provides:
- 📊 **Confidence Scores** for all classes
- 🔥 **Grad-CAM visualization** to show where the model is focusing
- 📄 **Downloadable PDF report** with:
  - Predicted disease
  - Explanation of "Why this class?" and "Why not others?"
  - Patient information
  - Annotated Grad-CAM images

✅ Easy-to-use GUI with:
- 🖼️ Image preview
- 🎨 Light/Dark theme toggle
- 📁 Upload image button
- 📥 Download report functionality

---

## 🧪 Sample GUI Preview

<img src="images/gui%20screenshot.jpg" alt="GUI Preview" width="700"/>


---

## 🧠 Grad-CAM Heatmap Example

<img src="images/gradcam_example.png" alt="Grad-CAM" width="700"/>

---

## 📁 How to Use

1. **Clone this repository**:
```bash
git clone https://github.com/yourusername/brain-tumor-detection.git
cd brain-tumor-detection

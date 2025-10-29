
# Breast Ultrasound Cancer Classification using Transfer Learning (BUSI Dataset)

## 📌 Project Overview
This project applies **deep learning for medical imaging** to classify breast ultrasound images as **benign or malignant** using the **BUSI dataset** (Al-Dhabyani et al., 2020).  
The objective is to support early detection in a **non-diagnostic assistive AI setting**, especially for **low-resource healthcare environments**.

This is an **explainable AI model**: beyond prediction, it generates **Grad-CAM heatmaps** to highlight regions contributing to its decision — a critical requirement for trust in medical AI.

> **Note:** This is a research/educational prototype, not a medical device.  

---

## 🎯 Learning & Research Goals
| Goal | Description |
|---|---|
Build a clinically-motivated CV system | Focus on a real medical application  
Use transfer learning | EfficientNet-B0 for high accuracy with low compute  
Ensure explainability | Grad-CAM to interpret model focus  
Follow reproducible ML practices | Structured repo + metrics + logs  
Practice ethical AI | Privacy, bias, and safety considered  

---

## 🧠 Problem Statement
Breast cancer is one of the leading causes of mortality among women.  
Ultrasound is widely accessible, but **interpretation quality varies** with operator skill and workload.

This project aims to create an **AI-assisted triage tool** to support clinicians by flagging potentially malignant lesions.

---

## ✅ Project Features
- Transfer Learning using **EfficientNet-B0**
- **Binary classification**: benign vs malignant
- **Grad-CAM heatmaps** for interpretability
- **Data augmentation** for robustness
- **Weighted loss** to address class imbalance
- Runs in **Google Colab (free GPU)**

---

## 📂 Repository Structure

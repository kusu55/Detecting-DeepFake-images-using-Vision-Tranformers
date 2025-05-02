# Detecting Deepfake Images using Vision Transformers

This project presents a deep learning solution for detecting deepfake images using **Vision Transformers (ViT)**. It includes model training, evaluation, and a simple user interface for real-time image classification with audio feedback.

---

## 📁 Project Structure

### 🔍 1. Model Development
**Notebook:** [`Detecting_Deepfake_Images_using_Vision_transformers.ipynb`](./Detecting_Deepfake_Images_using_Vision_transformers.ipynb)

- Dataset: [Kaggle Deepfake and Real Images](https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images)
- Architecture: Vision Transformer (`ViTForImageClassification`)
- Libraries: Hugging Face Transformers, PyTorch, NumPy, Pandas
- Key Features:
  - Data augmentation (resizing, flipping, jitter)
  - Evaluation metrics: Accuracy, F1-score, ROC-AUC
  - Achieved ~96.68% accuracy

---

### 💻 2. User Interface
**Notebook:** [`User InterFace Creation for Detecting Deepfakes.ipynb`](./User%20InterFace%20Creation%20for%20Detecting%20Deepfakes.ipynb)

- Built using **Gradio** for drag-and-drop interface
- Accepts image uploads and returns predictions (`Real` or `Fake`)
- Integrates Text-to-Speech for audible feedback

---

## 📊 Project Presentation

The complete project overview, methodology, and results are summarized in the following presentation:

📎 **[Project PPT (PDF)](./PROJECT%20PPT.pdf)**

---

## 🛠 Requirements

- OS: Windows/macOS
- Python 3.11.11+
- Libraries: 
  - `transformers`
  - `torch`
  - `gradio`
  - `datasets`
  - `numpy`, `matplotlib`, `pandas`

Hardware:
- 16GB RAM, NVIDIA GPU recommended for training

---

## 📌 Results Summary

- Accuracy: **96.68%**
- F1 Score: **0.9668**
- ROC-AUC: **0.98**

---

## ✅ Conclusion

This project demonstrates the effectiveness of **Vision Transformers** for high-accuracy deepfake detection, contributing to digital media integrity and misinformation control.


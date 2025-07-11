# 🧠 Brain Tumor Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to classify brain MRI scans into two categories: **tumor** and **no tumor**. Built using TensorFlow/Keras and OpenCV, the model is trained on grayscale MRI images and achieves high accuracy in detecting the presence of brain tumors. It has potential applications in medical diagnostics for early tumor identification.

---

## 📂 Dataset

The dataset contains labeled MRI images of brain scans:

* `yes/` – MRI images with tumor
* `no/` – MRI images without tumor
  Dataset Source: [Kaggle – Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy, Matplotlib
* scikit-learn

---

## 🚀 Features

* Image preprocessing (grayscale, resizing, normalization)
* CNN model for binary classification
* Real-time tumor prediction on new MRI images
* Easy to extend with Streamlit for web UI

---

## 📈 Sample Result

* **Training Accuracy**: \~95%
* **Validation Accuracy**: \~92%

---

## 📦 Run the Project

```bash
# Mount Google Drive if using Colab
from google.colab import drive
drive.mount('/content/drive')

# Then follow with your preprocessing and model training code
```

---

## 🔮 Future Enhancements

* Multiclass tumor type classification
* Integration with cloud-based diagnostic tools
* Streamlit or Flask web interface for doctor-friendly usage


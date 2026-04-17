# 🧠 Brain Tumor Classification using Transfer Learning & Grad-CAM

## 📌 Overview

This project focuses on detecting and classifying brain tumors from MRI images using **Deep Learning (Transfer Learning)**. It also uses **Grad-CAM (Gradient-weighted Class Activation Mapping)** to visualize which regions of the image influenced the model’s prediction.

---

## 🚀 Features

* 🧠 Brain tumor classification (Glioma, Meningioma, Pituitary, No Tumor)
* ⚡ Transfer Learning using pre-trained CNN models
* 🔥 Grad-CAM visualization for model explainability
* 📊 High accuracy (~98%)
* 🖼️ MRI image preprocessing and prediction pipeline

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

---

## 📂 Dataset

The dataset consists of brain MRI images categorized into:

* Glioma
* Meningioma
* Pituitary
* No Tumor

---

## 🧠 Model Approach

* Used **Transfer Learning** with a pre-trained CNN model
* Fine-tuned layers for better performance
* Trained on labeled MRI dataset
* Achieved high validation accuracy

---

## 🔥 Grad-CAM Visualization

Grad-CAM helps in understanding **why the model made a prediction** by highlighting important regions in the image.

### Function Used:

```python
VizGradCAM(model, image)
```

### What it does:

* Finds the last convolutional layer
* Computes gradients for predicted class
* Generates a heatmap
* Overlays heatmap on original image

---

## 📸 Output Example

* Original MRI Image
* Heatmap showing tumor focus area
* Combined visualization

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/brain-tumor-classification.git
cd brain-tumor-classification
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📈 Results

* Accuracy: ~98%
* Model successfully identifies tumor types
* Grad-CAM provides clear visual explanations

---

## ⚠️ Note

* Ensure dataset path is correct
* Images should be preprocessed before prediction

---

## 🎯 Future Improvements

* Deploy as web application
* Add real-time MRI upload system
* Improve model generalization
* Integrate with medical datasets

---

## 🙌 Acknowledgement

This project is built for educational and research purposes in medical image analysis.

---

## 📬 Contact

For queries or collaboration:

* GitHub: your-profile-link

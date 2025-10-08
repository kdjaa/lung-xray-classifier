

# 🫁 Lung X-ray Classifier (Transfer Learning)

### 🧩 Overview
This project applies transfer learning to classify chest X-ray images into **Normal**, **Lung Opacity**, and **Viral Pneumonia** categories.  
It uses pre-trained CNN architectures for feature extraction and fine-tuning to improve medical image classification accuracy.

---

### ⚙️ Model & Techniques
- **Base Models:** DenseNet121, ResNet50, or EfficientNetB0 (fine-tuned on the dataset)
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib
- **Data Augmentation:** Random rotations, flips, and rescaling
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  

---

### 📊 Results
- Training Accuracy: **≈ 92%**
- Validation Accuracy: **≈ 94%**
- Evaluation metrics: Confusion Matrix, Precision, Recall, and F1-score

---

### 📂 Dataset
- [lung disease Dataset – Kaggle](https://www.kaggle.com/datasets/fatemehmehrparvar/lung-disease)
- Custom split into **train**, **validation**, and **test** sets.

---

### 🧠 Skills Highlighted
Transfer Learning • Convolutional Neural Networks (CNNs) • Image Classification • Medical Imaging • Data Augmentation

---

### 🚀 How to Run
```bash
git clone https://github.com/khadigaahmed/lung-xray-classifier.git
cd lung-xray-classifier
pip install -r requirements.txt
jupyter notebook

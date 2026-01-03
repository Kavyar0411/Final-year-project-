# Heart Attack Risk Prediction using Retinal Images

## 📌 Overview
This project focuses on predicting the risk of heart attack using **retinal fundus images**. Retinal blood vessels reflect cardiovascular health, making retinal imaging a **non-invasive and effective method** for early heart disease risk assessment.

The system uses **image preprocessing, feature extraction, and machine learning techniques** to classify patients as **Normal** or **High Risk**.

---

## 🎯 Objectives
- Analyze retinal images for cardiovascular indicators
- Extract meaningful vascular features
- Predict heart attack risk using machine learning models
- Provide early risk assessment support

---

## 🧠 Key Concepts
- Medical Image Processing
- Feature Extraction
- Machine Learning Classification
- Retinal Vessel Segmentation

---

---

## 🖼️ Dataset
- Retinal fundus images
- Two classes:
  - Normal
  - High Risk
- Dataset used only for academic and research purposes

---

## 🔄 Methodology

### 1. Image Preprocessing
- Image resizing
- Noise reduction
- Normalization
- Contrast enhancement

### 2. Feature Extraction
- Blood vessel segmentation
- Texture and intensity analysis
- Extraction of vascular patterns related to cardiovascular health

### 3. Model Training
- Machine learning / deep learning models
- Transfer learning using pretrained models
- Bottleneck feature extraction for efficient training

### 4. Prediction
- Input retinal image
- Model predicts heart attack risk level
- Output: Normal / High Risk

---

## 🛠️ Technologies Used
- Python
- TensorFlow
- OpenCV
- NumPy
- SciPy
- Scikit-learn
- Matplotlib

---

## 🚀 How to Run

### Clone Repository
```bash
git clone https://github.com/your-username/heart-attack-risk-prediction.git
cd heart-attack-risk-prediction
```
```bash
pip install -r requirements.txt
python retrain.py
python label_image.py --image path_to_image.jpg
```

---

## Installation
* 1.innstall ANACONDA
* 2.Open ANACONDA NAVIGATOR
* 3.Create New Environment with the project name
* 4.home-project environment-install cmd.exe, and jupyter notebook
* 5.open cmd.exe in a project environment and execute the following commands one by one

```bash
pip install tensorflow
conda install -c conda-forge keras
conda install -c anaconda scikit-learn
conda install -c conda-forge opencv
conda install -c anaconda scikit-image
conda install -c anaconda flask
pip install pandas
pip install werkzeug==2.3.7
```
---
## Results

Successfully classifies retinal images into risk categories

Demonstrates feasibility of retinal-based cardiovascular screening

Suitable for early detection support systems
 
---
## Outcomes 



# 🐱🐶 Cat vs Dog Image Classifier

This project is a Deep Learning case study that uses **Convolutional Neural Networks (CNNs)** to classify images as either **Cat** or **Dog**.
It demonstrates image preprocessing, model building, evaluation, and prediction using **TensorFlow/Keras**.

---

## 📊 Features of the Project

* Image Preprocessing and Augmentation
* Model Building using Convolutional Neural Network (CNN)
* Accuracy and Loss Visualization
* Image Prediction (Cat or Dog)
* Saved Model for Future Inference
* Optional Web App using Streamlit

---

## 📁 Dataset

Dataset used:

* **Cat and Dog Dataset** (by TongPython)

Download from **[Dataset Download](https://www.kaggle.com/datasets/tongpython/cat-and-dog)**

---

## 📂 Project Structure

```
Cat-vs-Dog-Classifier/
│
├── cat_dog.ipynb              # Main Jupyter Notebook
├── requirements.txt           # Dependencies file
├── README.md                  # Project documentation
│
├── dataset/                   # (Optional) Folder for dataset
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   └── test/
│       ├── cats/
│       └── dogs/
│
├── model/                     # (Optional) Folder to store saved models
│   └── cat_dog_model.h5
│
└── results/                   # (Optional) Folder for output predictions
    └── sample_predictions/
```

---

## ⚙️ Requirements

Install the required dependencies before running the notebook:

### Required Libraries

```
tensorflow
numpy
pandas
matplotlib
scikit-learn
opencv-python
jupyter
```

### Install all dependencies at once:

```bash
pip install -r requirements.txt
```

---

## 🔧 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Cat-vs-Dog-Classifier.git
cd Cat-vs-Dog-Classifier
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

```bash
jupyter notebook cat_dog.ipynb
```

---

## 📊 Model Performance

* **Training Accuracy:** 97%
* **Validation Accuracy:** ~99%

---

## 💡 Future Improvements

* Implement data augmentation for better generalization
* Try transfer learning with models like VGG16 or ResNet50
* Build an interactive web app using Streamlit

---

## 👨‍💻 Author

**Manikandaa S**
🎓 Data Science Enthusiast | 💡 Passionate about AI & ML
🔗 [LinkedIn](https://www.linkedin.com/in/manikandaa-s-aa676225a) | [GitHub](https://github.com/Manikandaa148)

---

### ⭐ Don’t forget to star this repo if you found it helpful!


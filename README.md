# 🐱🐶 Cat vs Dog Image Classifier

This project is a Deep Learning-based **Image Classification Model** that predicts whether an image contains a **cat or a dog**.  
It is implemented using **TensorFlow/Keras** and trained on a dataset of cat and dog images.

---

## 🚀 Features
- Image classification using Convolutional Neural Networks (CNN)
- Trains and evaluates the model using TensorFlow/Keras
- Visualises model accuracy and loss graphs
- Predicts unseen images (cat or dog)

---

## 📂 Project Structure
Cat-vs-Dog-Classifier/
│
├── cat_dog.ipynb                # Your main notebook
├── requirements.txt             # All dependencies
├── README.md                    # Project description
│
├── dataset/                     # (Optional) Folder to store images
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   └── test/
│       ├── cats/
│       └── dogs/
│
├── model/                       # (Optional) Folder to store saved models
│   └── cat_dog_model.h5
│
└── results/                     # (Optional) Folder for prediction outputs
    └── sample_predictions/

---

🧠 Libraries Used

TensorFlow / Keras
NumPy
Pandas
Matplotlib
scikit-learn

## 📥 Dataset
Please use the **dataset download** from Kaggle at  Kaggle (TongPython’s “Cat and Dog” dataset)  to retrieve the images that you will use for training and testing.

---

## ⚙️ Requirements
Install the dependencies using:
```bash
pip install -r requirements.txt

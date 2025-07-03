# 🧥 Fashion Item Classification using Deep Learning

This project uses deep learning techniques to classify clothing items from grayscale images into 10 categories using the Fashion MNIST dataset. The model is deployed via a Streamlit web app, allowing users to upload images and receive predictions in real time.

---

## 📌 Problem Statement

Build an intelligent system that classifies fashion items into predefined categories such as T-shirt, Dress, Coat, Sneaker, etc., using grayscale images. The model is optimized for accuracy and deployed for real-time use.

---

## 🗃️ Dataset

- **Fashion MNIST** from Zalando Research
- 60,000 training images + 10,000 test images
- 10 classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot
- Grayscale 28x28 pixel images

---

## 🔧 Data Preprocessing

- Normalization to [0, 1]
- Reshaping to fit CNN input `(28, 28, 1)`
- Grayscale handling for real-time uploads

---

## 🧠 Model Architecture

### 1. **Baseline Model – MLP**
- Flatten → Dense(128, ReLU) → Dense(10, Softmax)
- Accuracy: ~88%

### 2. **Optimized Model – CNN**
- Conv2D → BatchNorm → MaxPooling (x3 layers with increasing filters)
- Dropout for regularization
- Dense → Softmax output layer
- Accuracy: ~92%

---

## 📈 Evaluation

- Accuracy
- Confusion Matrix
- Class-wise prediction confidence plots

---

## 🚀 Deployment

Deployed using **Streamlit**, featuring:
- Image Upload
- Real-time prediction with class label and confidence
- Deployed via **Pyngrok** for easy sharing

---

## 🛠️ Tech Stack

- Python
- TensorFlow & Keras
- Streamlit
- NumPy, Matplotlib
- Fashion MNIST Dataset

---

## 📦 Deliverables

- ✅ Python Code (`.ipynb`)
- ✅ Trained Model (`.h5`)
- ✅ Streamlit App Script
- ✅ Report PDF
- ✅ (Optional) Presentation

---

## 🔮 Future Scope

- Hyperparameter tuning
- Transfer Learning (e.g., MobileNetV2)
- Data Augmentation
- Cloud Hosting (AWS, GCP, Hugging Face Spaces)

---

## 📚 References

- [TensorFlow Docs](https://www.tensorflow.org/)

---

## 👩‍💻 Author

**Lavanya Bhamidipati**  
BSc Data Science & Business Analytics – Final Year Project

---


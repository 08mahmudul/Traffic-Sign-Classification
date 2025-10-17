# 🚦 Traffic Sign Classification using CNN

A deep learning project by **Mahmudul Hasan** 👨‍💻  
Using **Convolutional Neural Networks (CNN)** to classify different traffic signs with **99.23% accuracy**.

---

## 📘 Project Overview
The goal of this project is to **automatically classify traffic signs** using image recognition techniques.  
This type of model can be integrated into **autonomous vehicles** to help them recognize and respond to road signs effectively.

---

## 🧠 Dataset
The dataset used is the **German Traffic Sign Recognition Benchmark (GTSRB)** —  
a standard dataset containing over **50,000 images** of **43 different traffic sign classes**.

Each image was resized and normalized for training the CNN model.

---

## ⚙️ Steps Performed
1. **Data Preprocessing**  
   - Image resizing to 32x32  
   - Normalization  
   - One-hot encoding of labels  

2. **Model Building**  
   - Used **Convolutional Neural Network (CNN)**  
   - Layers:
     - Conv2D → ReLU → MaxPooling
     - Conv2D → ReLU → MaxPooling
     - Flatten → Dense → Dropout → Output layer (Softmax)

3. **Model Training**
   - Optimizer: **Adam**
   - Loss Function: **Categorical Crossentropy**
   - Epochs: 10 
   - Accuracy achieved: **99.23%**

4. **Model Evaluation**
   - Evaluated on test set using accuracy, confusion matrix & classification report.
   - Visualized sample predictions with Matplotlib.

---

## 🧩 Model Architecture

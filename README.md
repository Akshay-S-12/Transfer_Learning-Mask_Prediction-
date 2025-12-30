# 😷 Face Mask Detection Using Transfer Learning (VGG16)

This project implements a **Face Mask Detection system** using **Transfer Learning with VGG16**.  
The model classifies images into **With Mask** and **Without Mask** categories using a pre-trained deep learning model.

The goal is to demonstrate how **transfer learning** can be effectively used for image classification tasks with limited data.

---

## 📌 Features
- 🧠 Uses **VGG16 pre-trained on ImageNet**
- 🔁 Transfer Learning (frozen convolutional layers)
- 🖼️ Image classification: **With Mask / Without Mask**
- 📊 Training & validation accuracy visualization
- 💾 Trained model saved for reuse
- 🔍 Supports prediction on new images

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **VGG16 (Transfer Learning)**
- **OpenCV / skimage**
- **Matplotlib**
- **NumPy, Pandas**

---

## 📂 Project Structure
Mask-Prediction-VGG16/
│
├── train.py
├── Model_Transfer_Learning.h5
├── README.md
├── Maskdata/
│ ├── with_mask/
│ └── without_mask/
│
└── Maskdatatest/
├── with_mask/
└── without_mask/


## ⚙️ Model Architecture
- Base Model: **VGG16 (ImageNet weights)**
- Top Layers:
  - Flatten Layer
  - Dense Layer (Softmax, 2 classes)
- Optimizer: **Adam**
- Loss Function: **Categorical Crossentropy**

    ## 📦 Dataset
Due to GitHub file size limitations, the datasets are **not uploaded to this repository**.

This project uses **two datasets**:

- 🔗 **Training Dataset**:  
  https://drive.google.com/drive/folders/1ITAsNudC03S5I2sOMfl_YujoZ_TZ24uK

- 🔗 **Testing Dataset**:  
  https://drive.google.com/drive/folders/1by21bHauktDylbgmLz3OzhAZ4KVSk13S

After downloading, place the datasets in the following structure:

Maskdata/
├── with_mask/
└── without_mask/

Maskdatatest/
├── with_mask/
└── without_mask/


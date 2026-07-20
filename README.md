# 🤖 Hand Gesture Recognition using CNN

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to recognize hand gestures from images.

The model is trained on the LeapGestRec dataset and can classify hand gestures into multiple categories.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pillow (PIL)

---

## 📂 Project Structure

```
Hand-Gesture-Recognition/
│
├── data/
│   └── leapGestRec/
├── source code/
│   └── main.py
├── test.jpeg.png
├── hand_gesture_model.keras
├── requirements.txt
└── README.md
```

---

## 🧠 CNN Architecture

- Rescaling Layer
- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Flatten Layer
- Dense Layer
- Dropout Layer
- Softmax Output Layer

---

## ⚙️ Training Configuration

| Parameter | Value |
|------------|---------|
| Image Size | 128 × 128 |
| Batch Size | 32 |
| Epochs | 5 |
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |

---

## 🚀 How to Run

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python "source code/main.py"
```

---

## 📈 Features

- Hand Gesture Classification
- CNN-Based Deep Learning Model
- Model Training and Validation
- Test Image Prediction
- Confidence Score Display
- Accuracy and Loss Visualization

---

## 📊 Dataset

Dataset used: LeapGestRec Hand Gesture Dataset

Contains 10 gesture classes and thousands of training images.

---

## 🎯 Output

The system predicts:

- Gesture Class
- Confidence Score
- Prediction Probability Graph

Example:

```
Predicted Gesture : Palm
Confidence : 98.75%
```

---

## 🔮 Future Enhancements

- Real-Time Webcam Recognition
- More Gesture Classes
- Mobile Application Integration
- Transfer Learning Models

---

## 👨‍💻 Author
Naganjali

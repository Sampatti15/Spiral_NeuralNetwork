# 🌀 Spiral Neural Network Classifier

## 📌 Overview

This project demonstrates the use of a Neural Network to classify complex spiral-shaped data into three categories:

- 🔴 Red
- 🟢 Green
- 🔵 Blue

The model is trained on spiral data and learns non-linear decision boundaries to accurately predict the class of new unseen points.

---

## 🎯 Project Goal

To design a Neural Network that accepts input coordinates (X1, X2) and predicts whether the point belongs to the Red, Green, or Blue category based on the training data.

---

## 🛠️ Technologies & Libraries Used

- Python
- NumPy
- TensorFlow/Keras
  - Sequential Model
  - Dense Layers
- Scikit-Learn
  - StandardScaler
- Matplotlib

---

## 📊 Dataset

The dataset consists of spiral-shaped data points distributed across three classes:

| Class Label | Category |
|------------|----------|
| 0 | Red |
| 1 | Green |
| 2 | Blue |

Each data point contains:
- X1 Coordinate
- X2 Coordinate

Target:
- Class Label (0, 1, or 2)

---

## 🔄 Project Workflow

1. Generate spiral dataset using NumPy
2. Visualize the dataset using Matplotlib
3. Scale features using StandardScaler
4. Build a Neural Network using Keras Sequential API
5. Add Dense hidden layers with ReLU activation
6. Train the model on spiral data
7. Predict classes for new data points
8. Visualize prediction results

---

## 🧠 Model Architecture

Input Layer (2 Features)
↓
Dense Layer (ReLU)
↓
Dense Layer (ReLU)
↓
Dense Layer (ReLU)
↓
Output Layer (Softmax)
↓
Red / Green / Blue Prediction

---

## 🚀 Features

✔ Spiral data generation

✔ Data visualization

✔ Feature scaling

✔ Neural Network training

✔ Multi-class classification

✔ New point prediction

✔ Prediction visualization

---

## 📈 Example Prediction

Input Point:

(0.1, -0.5)

Predicted Output:

Blue

---

## 📷 Results
<img width="881" height="676" alt="New Test Point" src="https://github.com/user-attachments/assets/09840e80-335b-45a4-b20d-833f1cda8aea" />
<img width="863" height="678" alt="Model loss and accuracy" src="https://github.com/user-attachments/assets/340b228c-c53a-46f7-8ed9-e0b9161ab1a7" />


The project visualizes:

- Spiral Dataset
- Neural Network Predictions
- New Test Point Classification
- Predicted Class Labels

---

## 👩‍💻 Author

**Sampatti Borse**

Machine Learning Enthusiast

If you found this project useful, consider giving it a ⭐ on GitHub!

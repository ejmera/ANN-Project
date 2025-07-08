# 🧠 Customer Classification using ANN with Categorical Data

This project demonstrates how to classify customers using Artificial Neural Networks (ANN) based on categorical features such as gender, region, and membership level.

## 📌 Project Overview

- **Goal:** To build a neural network that classifies customers into predefined segments using only categorical inputs.
- **Data:** Synthetic or real-world dataset with categorical features (e.g., gender, region, customer type).
- **Model:** Feedforward Artificial Neural Network implemented in Python.

## 📂 Files

| File Name       | Description                                  |
|----------------|----------------------------------------------|
| `1_model.py`    | ANN model implementation, training & testing |
| `2_dataset.csv` | Customer dataset with categorical features   |

## 🛠️ Technologies Used

- Python 🐍  
- TensorFlow / Keras  
- Pandas & NumPy  
- Scikit-learn (for preprocessing)

## ⚙️ Workflow

1. Load and preprocess the dataset (label encoding, one-hot encoding).
2. Normalize inputs if necessary.
3. Define and train the ANN model.
4. Evaluate performance using metrics like accuracy, confusion matrix, etc.

## 📊 Example Categorical Features

- Gender (Male/Female)
- Region (North, South, East, West)
- Membership Type (Bronze, Silver, Gold)

## 🚀 How to Run

```bash
# Clone this repository
git clone https://github.com/your-username/customer-classification-ann

# Install required libraries
pip install -r requirements.txt

# Run the model
python 1_model.py
```
---

📄 This project is licensed under the MIT License — © Enes Bulut

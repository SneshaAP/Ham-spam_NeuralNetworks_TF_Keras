# Spam vs Ham Detection using Neural Networks (TensorFlow + Keras)

This project implements a simple neural network using Keras to classify SMS messages as **spam** or **ham**.

## 📁 File Description

- `ham&spam_neuralnetworks_tf_keras_snesha.py`: Main Python script implementing the model.
- `requirements.txt`: Python dependencies required to run the project.
- `README.md`: This file!

## 📦 Requirements

Install the requirements via:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Ensure your dataset is in the correct path (`/content/archive (6).zip`) or update it accordingly.
2. Run the script:

```bash
python ham&spam_neuralnetworks_tf_keras_snesha.py
```

## 🔍 Model Summary

- Input: SMS messages vectorized using CountVectorizer
- Model: 3-layer feedforward neural network
- Output: Binary classification (Ham/Spam)

## 📈 Training Info

- Optimizer: Adam
- Loss: Binary Crossentropy
- Epochs: 10
- Evaluation: Accuracy, Loss (train and validation)

## 🧠 Prediction

The model includes an example of predicting a new message:
```python
"let us go out" ➝ Ham or Spam
```

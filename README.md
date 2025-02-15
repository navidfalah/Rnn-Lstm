# Regression with RNN and LSTM using PyTorch 📈🤖

This project demonstrates **regression** using **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)** networks on the **California Housing Dataset**. The goal is to predict housing prices using sequential data modeling. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **PyTorch** to build and train RNN and LSTM models for regression. 🤖📈
- Leverages the **California Housing Dataset** for training and validation. 🧠🔍
- Implements data preprocessing, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch scikit-learn
```

---

## Usage 🖥️

1. **Load Dataset**: The script loads the California Housing Dataset.
2. **Preprocess Data**: Applies standardization and splits the data into training and test sets.
3. **Build Models**: Defines RNN and LSTM models for regression.
4. **Train Models**: Trains the models using the training set.
5. **Evaluate Models**: Evaluates the models' performance on the test set.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Loads and preprocesses the California Housing Dataset.
  - Splits the data into training and test sets.

- **Model Definition**:
  - Defines RNN and LSTM models with fully connected layers.
  - Uses mean squared error (MSE) loss for training.

- **Training**:
  - Trains the RNN and LSTM models using the training set.
  - Tracks training loss over epochs.

- **Evaluation**:
  - Evaluates the models' performance on the test set.
  - Prints the test MSE for both models.

---

## Results 📊

- **Training Loss**: The models achieve low training loss over epochs.
- **Test MSE**: Evaluates the models' performance on the test set.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/50, Loss: 1.123
Epoch 2/50, Loss: 0.987
...
RNN Test MSE: 0.045
LSTM Test MSE: 0.032
```

---

## Dependencies 📦

- `torch`
- `scikit-learn`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝

# power-plant-energy-prediction-pytorch
# Power Plant Energy Prediction using Artificial Neural Networks

## Overview
This project develops an Artificial Neural Network (ANN) using PyTorch to predict the electrical energy output (PE) of a Combined Cycle Power Plant based on environmental conditions. The model learns the relationship between atmospheric variables and power generation, demonstrating the application of deep learning for regression tasks.

---

## Problem Statement

Power plant operators aim to accurately predict electrical energy output under varying environmental conditions. Accurate predictions help improve operational planning, optimize energy production, and enhance overall plant efficiency.

The objective of this project is to build a deep learning regression model capable of predicting power output from environmental measurements.

---

## Dataset

**Dataset:** Combined Cycle Power Plant (CCPP)

### Features

- Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

### Target

- Electrical Energy Output (PE)

---

## Technologies Used

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Train-Test Split
4. Feature Scaling
5. Convert Data to PyTorch Tensors
6. Build ANN Model
7. Model Training
8. Validation
9. Model Evaluation
10. Prediction Visualization

---

## Model Architecture

Input Layer (4 Features)

↓

Hidden Layer (ReLU)

↓

Hidden Layer (ReLU)

↓

Output Layer (1 Neuron)

---

## Loss Function

- Mean Squared Error (MSELoss)

## Optimizer

- Adam Optimizer

---

## Evaluation Metrics

The model performance is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Key Features

- End-to-end Deep Learning Regression Pipeline
- Data Standardization using StandardScaler
- Mini-batch Training using DataLoader
- Custom ANN built with PyTorch
- Model Checkpoint Saving
- Training & Validation Loss Visualization
- Performance Evaluation using Regression Metrics

---

## Project Structure

```
power-plant-energy-prediction/

│── data/
│     └── Folds5x2_pp.xlsx

│── notebooks/
│     └── power_plant_energy_prediction_ann.ipynb

│── models/
│     └── best_model.pt

│── images/
│     ├── training_loss.png
│     └── prediction_plot.png

│── requirements.txt

│── README.md
```

---

## Results

| Metric | Value |
|---------|------:|
| Training MSE | 20.44 |
| Testing MSE | 18.77 |
| R² Score | 93.44% |

The ANN model achieved an **R² Score of 93.44%**, indicating that it explains approximately **93% of the variance** in the power plant's energy output. The low training and testing MSE values demonstrate good predictive performance and strong generalization on unseen data.

---

## Author

**Rohit Singh Rawat**

- LinkedIn: https://www.linkedin.com/in/rohit-singh-rawat1407/
- GitHub: https://github.com/rohitCoder-14


# ipl-score-prediction

This repository contains a machine learning project that predicts the total score in an IPL (Indian Premier League) match based on historical match data using a neural network model built with Keras and TensorFlow.

## 📊 Overview

This project performs:

- Data preprocessing and feature engineering on IPL dataset
- Exploratory Data Analysis (EDA) with visualizations
- Label encoding and feature scaling
- Neural Network training using TensorFlow/Keras
- Score prediction interface using ipywidgets for interactive input

## 🧠 Technologies Used

- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn (for preprocessing)
- TensorFlow + Keras (for building the neural network)
- ipywidgets (for interactive UI in Jupyter Notebook)

## 📁 Dataset

The dataset file used is `ipl_dataset.csv`, which should be placed in the root directory of the project.

## 📈 Exploratory Data Analysis

- Number of matches per venue
- Top 10 batsmen by runs
- Top 10 bowlers by wickets
- Correlation heatmap of numerical features

## 🏗️ Model Architecture

- Input layer for 9 features
- Hidden layers: [512, 216] neurons with ReLU activation
- Output layer with 1 neuron (regression output)
- Loss function: Huber Loss
- Optimizer: Adam

## 🔄 Training

The model is trained for 10 epochs with batch size 64. The loss curve is plotted to evaluate convergence.

## 🧪 Evaluation

Evaluation metrics used:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## 🎮 Interactive Score Prediction

Implemented an interactive UI using `ipywidgets` to predict total IPL scores based on inputs such as:
- Batting Team
- Bowling Team
- Venue
- Current Runs, Wickets, Overs
- Striker and Bowler

## 📦 Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow ipywidgets
```

## ▶️ Run the Project

1. Load `ipl_dataset.csv` in the same folder.
2. Run the notebook or Python script in Jupyter.
3. Use the interactive widgets to predict scores.

## 📜 License

This project is open-source and available under the MIT License.

---

**Author:** Chenna Kesava  
**Tech Stack:** Python, TensorFlow, ipywidgets  

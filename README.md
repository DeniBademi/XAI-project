# Stock Price Prediction with Explainable AI (XAI)

This project implements a deep learning model for stock price prediction with explainability features.

## Project Overview

The project uses a combination of LSTM network and attention mechanisms to predict stock prices, with a focus on making the predictions interpretable through XAI techniques (Integraded Gradients and LIME)

## Features

- Stock price prediction using LSTM and with attention mechanism
- Data preprocessing and feature engineering
- Model training with early stopping and checkpointing
- Explainability analysis using Integrated Gradients and LIME
- Visualization of predictions and explanations

## Project Structure

```
.
├── data/              # Directory containing stock data
├── models/            # Directory for saved model checkpoints
├── main.ipynb         # Main Jupyter notebook with implementation
├── requirements.txt   # Project dependencies
└── README.md          # This file
```

## Dependencies

The project requires the following Python packages:
- numpy==1.26.4
- pandas==1.5.3
- tensorflow==2.19.0
- keras==3.8.0
- matplotlib==3.9.2
- scikit-learn==1.3.0
- lime==0.2.0.1

## Installation

1. Clone this repository
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Unzip the dataset zip file in data directory

## Usage

Open and run `main.ipynb` in Jupyter Notebook or IDE of your choice

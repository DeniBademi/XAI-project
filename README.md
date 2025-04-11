# Stock Price Prediction with Explainable AI (XAI)

This project implements a deep learning model for stock price prediction with explainability features.

## Project Overview

The project uses a combination of LSTM network and attention mechanisms to predict stock prices, with a focus on making the predictions interpretable through XAI techniques (Integraded Gradients and LIME)

## Features

- Stock price prediction using LSTM with attention mechanism
- Data preprocessing and feature engineering
- Model training with early stopping and checkpointing
- Explainability analysis using LIME
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

## Usage

1. Open `main.ipynb` in Jupyter Notebook
2. Run the cells in sequence to:
   - Load and preprocess the data
   - Train the model
   - Generate predictions
   - Analyze model explanations using Integrated Gradients and LIME

## License

This project is licensed under the MIT License - see the LICENSE file for details.

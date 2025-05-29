# Quantum Boltzmann Machine (QBM) for Financial Market Prediction

This repository explores the application of Quantum Boltzmann Machines (QBMs) in predicting financial markets. It implements various models to analyze and forecast market trends.

## Repository Structure

- `Data/`: Contains datasets used for training and testing the models.
- `LSTM+QBM.ipynb`: Jupyter Notebook implementing a hybrid model combining Long Short-Term Memory (LSTM) networks with Quantum Boltzmann Machines.
- `MainModel.ipynb`: Jupyter Notebook implementing the primary QBM model for financial market prediction.
- `linearregression.ipynb`: Jupyter Notebook implementing a baseline Linear Regression model for comparison purposes.
- `dataset_MRK_prediction.csv`: Sample dataset used for market prediction.

## Implemented Models

### 1. Linear Regression (`linearregression.ipynb`)

This notebook implements a baseline Linear Regression model to predict financial market trends. Linear regression is a fundamental statistical method that models the relationship between a dependent variable and one or more independent variables by fitting a linear equation to observed data.

### 2. Quantum Boltzmann Machine (QBM) (`MainModel.ipynb`)

This notebook focuses on implementing a Quantum Boltzmann Machine for financial market prediction. QBMs are quantum counterparts of classical Boltzmann Machines, leveraging quantum mechanics to model complex distributions. They are particularly suited for capturing intricate patterns in financial data that classical models might overlook.

### 3. Hybrid LSTM and QBM Model (`LSTM+QBM.ipynb`)

This notebook presents a hybrid model that combines Long Short-Term Memory (LSTM) networks with Quantum Boltzmann Machines. LSTMs are a type of recurrent neural network capable of learning long-term dependencies, making them effective for time-series prediction. Integrating LSTMs with QBMs aims to enhance predictive performance by leveraging both temporal dynamics and complex pattern recognition in financial data.

## Dataset

The repository includes the data folder, which serves as a sample dataset for market prediction models. This dataset contains historical financial data used to train and evaluate the implemented models.

## References

For further reading on the application of Quantum Boltzmann Machines in quantitative finance, consider exploring the following resources:

- [Quantum Boltzmann Machines: Applications in Quantitative Finance](https://arxiv.org/abs/2301.13295)
- [qbm-quant-finance GitHub Repository](https://github.com/cameronperot/qbm-quant-finance)

These resources provide insights into the theoretical foundations and practical implementations of QBMs in financial market analysis. 
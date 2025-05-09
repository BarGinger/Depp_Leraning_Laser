# Depp_Leraning_Laser
Deep learning (INFOMDLR) - Assignment 1

## Project Overview
This project explores the use of RNN-based architectures (RNN, LSTM, and GRU) for time series forecasting on a laser measurement dataset. Despite achieving good performance on training and validation sets, the models demonstrated limited generalization ability on the test set. This highlights the need for more rigorous data preprocessing and systematic hyperparameter optimization to improve performance on this type of dataset.

### Group Number: 22

### Team Members:
1. **Mahshid Jafar Tajrishi - 2931788**
2. **Bar Melinarskiy - 2482975**
3. **Cis van Aken - 7295758**
4. **Simon van Klompenburg - 0903999**

## Project Structure
The project is organized as follows:
- **`RNN.ipynb`**: Notebook containing the implementation, training, and evaluation of the Vanilla RNN model.
- **`LSTM.ipynb`**: Notebook containing the implementation, training, and evaluation of the LSTM model.
- **`GRU.ipynb`**: Notebook containing the implementation, training, and evaluation of the GRU model.
- **`Data/`**: Directory containing the laser measurement dataset (`Xtrain.mat` and `Xtest.mat`).
- **`Models/`**: Directory for saving trained model weights and best hyperparameters.
- **`Output/`**: Directory for saving evaluation metrics, plots, and other results.
- **`README.md`**: Project documentation and instructions.

## Prerequisites
- Python 3.12
- Required libraries: `torch`, `numpy`, `pandas`, `matplotlib`, `seaborn`, `optuna`, `scipy`, `tqdm`, `scikit-learn`

## How to Run the Project
1. Clone the repository and navigate to the project directory.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the desired notebook (`RNN.ipynb`, `LSTM.ipynb`, or `GRU.ipynb`) to train the corresponding model and evaluate its performance.
4. Results, including evaluation metrics and plots, will be saved in the `Output/` directory.
# Stock Price Prediction using CNN-BiLSTM

This project predicts future stock prices using a CNN-BiLSTM deep learning model.  
It learns patterns from historical stock price data and forecasts future values.

---

## Project Description

Stock prices are time-series data and are difficult to predict using traditional methods.  
In this project:

- CNN (Convolutional Neural Network) extracts important features from stock prices  
- BiLSTM (Bidirectional LSTM) learns patterns in both forward and backward directions  
- The model predicts future stock prices based on past values  

---

## Model Used

- CNN for feature extraction  
- Bidirectional LSTM for sequence learning  
- Dense layers for final prediction  

Forecast Steps: `75`

---

## Dataset

- Data is taken from a CSV file  
- Uses historical stock prices (Close price)  
- Data split:
  - 75% Training  
  - 25% Testing  

---

## Data Preprocessing

- Handle missing values  
- Normalize data using Min-Max Scaling  
- Create time-series sequences using sliding window  
- Convert data to PyTorch tensors  

---

## Training Details

- Framework: PyTorch  
- Loss Function: Mean Squared Error (MSE)  
- Optimizer: Adam  
- Batch Size: Configurable  
- Epochs: Configurable  

---

## Output

- Training loss graph  
- Actual vs Predicted stock price plot  
- Multi-step future price prediction  

---

## Libraries Used

- Python  
- PyTorch  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---


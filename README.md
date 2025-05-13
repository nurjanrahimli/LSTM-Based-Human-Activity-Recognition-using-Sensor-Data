# LSTM-Based-Human-Activity-Recognition-using-Sensor-Data
LSTM model to recognize human physical activities using time-series sensor data.
# LSTM-Based Human Activity Recognition using Sensor Data

This project demonstrates the use of Long Short-Term Memory (LSTM) networks for classifying human physical activities using time-series sensor data. The data comes from smartphone accelerometer and gyroscope readings.

## 📊 Dataset

- Source: UCI HAR Dataset  
- Shape: 561 features per instance  
- Classes:  
  - WALKING  
  - WALKING_UPSTAIRS  
  - WALKING_DOWNSTAIRS  
  - SITTING  
  - STANDING  
  - LAYING

## 🚀 Goal

Train an LSTM model that can classify human activities with high accuracy using only raw sensor time-series data.

## 🛠️ Model Architecture

- 2 LSTM layers with 100 units each  
- Dropout for regularization  
- Dense layer with ReLU  
- Final softmax layer with 6 outputs  
- Loss: Sparse Categorical Crossentropy  
- Optimizer: Adam

## 📈 Accuracy

Achieved over **90% accuracy** on the test set.

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 How to Run

1. Clone the repo  
2. Place `train.csv` and `test.csv` in the root directory  
3. Install requirements:


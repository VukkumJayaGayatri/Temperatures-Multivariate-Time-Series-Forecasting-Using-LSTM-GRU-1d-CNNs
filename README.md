# Temperatures-Multivariate-Time-Series-Forecasting-Using-LSTM-GRU-1d-CNNs

## 🔍 Project Highlights  
- **Architecture**: Compared **LSTM, GRU, and 1D-CNN** performance on multivariate weather data (temperature + 10+ features).  
- **Key Result**: **Ensemble model reduced RMSE by 12%** vs best single model (CNN-LSTM hybrid).  
- **Deployment**: REST API (Flask) with automated data pipeline for hourly retraining.  

## 🛠️ Tech Stack  
- **Models**: LSTM, GRU, 1D-CNN (TensorFlow/Keras)  
- **Data Processing**: Pandas, NumPy, Scikit-learn  
- **Deployment**: Flask, Docker  

## 📈 Results  
| Model | RMSE (°C) | Training Time |  
|-------|----------|--------------|  
| LSTM | 2.3 | 45min |  
| **CNN-LSTM (Ensemble)** | **2.02** | 68min |  

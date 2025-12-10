# toronto-temperature-forecasting-cnn-lstm
This project forecasts next-day mean air temperature in Toronto using three deep-learning approaches: LSTM, GRU, and CNN. It includes three separate notebooks, each demonstrating a different model architecture.

📊 Dataset

Source: Environment & Climate Change Canada (Station 51459)

1,095 daily records (2018–03–18 to 2021–03–16)

Variable: Mean daily temperature (°C)

🧠 Models

LSTM Notebook — sequence forecasting with engineered seasonal features

GRU Notebook — PyTorch implementation for comparison

CNN Notebook — 1D convolution over rolling windows

⚙️ Method Summary

Time-series preprocessing, lag/rolling features

Seasonal encodings (sin/cos)

Chronological train–test split

MAE, RMSE, R², sMAPE, and tolerance accuracy (±2°C, ±3°C, ±5°C)

Trained on Google Colab (GPU)

<img width="1783" height="996" alt="image" src="https://github.com/user-attachments/assets/7f3bc414-1453-43bc-a4a9-0ac86e3ba6c3" />

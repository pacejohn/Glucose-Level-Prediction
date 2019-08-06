Glucose-Level-Prediction
Blood glucose level prediction using SARIMA and LSTM

The purpose of this project is to predict blood glucose levels using synthetic data generated using software by Jinyu Xie called Simglucose v0.2.1, "a Type-1 Diabetes simulator implemented in Python for Reinforcement Learning purpose."  (Jinyu Xie. Simglucose v0.2.1 (2018) [Online]. Available: https://github.com/jxx123/simglucose. (Accessed 2019).)

Steps in the process:
1.  Data was generated for children, adolescents, and adults using Simglucose.  The create_data.py script will generate the data.
2.  The data was processed into a usable format for the Jupyter notebooks.
3.  For SARIMA, the Jupyter notebook "glucose_lstm.ipynb" was run to train and make predictions.
4.  For LSTM, the Jupyter notebook "glucose_SARIMAX.ipynb" was run to train and make predictions.



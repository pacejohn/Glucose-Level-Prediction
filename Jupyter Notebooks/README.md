This folder contains the Jupyter Notebooks used in the pipeline.

process_input_files.ipynb manipulates the input files generated with the create_data.py script so they can be used with glucose_lstm_GPU0.ipynb and glucose_SARIMAX.ipynb.

glucose_SARIMAX.ipynb performs the analysis of the blood glucose data using SARIMAX.

glucose_lstm_GPU0.ipynb performs the analysis of the bllod glucose data using an LSTM.

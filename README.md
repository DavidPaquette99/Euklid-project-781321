# Euklid-project-781321
Machine Learning Course: Euklid project  
Submission by: Marchioni Gian Lorenzo - Paquette David - Tomasella Elena

## Method1: combined ARIMA and LSTM 

This code includes data cleaning and preprocessing, as well as the implementation of LSTM and ARIMA models. The predicted prices of the two are combined to be inout of an AI trader. Finally, a main_2() function is providing the readers a further try of another approach to the task.  The code is structured using functions, to get advantage of the peculiar modularity of Python.  Note: a draft() function is left at the end of the code, but useless.

## Method2: ANFIS classfier  
This directory is self-sufficient and includes everything needed to perform feature engineering, training, and evaluations. It contains:
- A notebook `anfis.ipynb` where the actual feature engineering, training, and evaluations are performed.
- Preprocessed datasets, ending with `_ok.csv`.
- A `utilities.py` file with custom calculations and plotting functions, written mainly to de-clutter the notebook.
- The modified ANFIS modules `anfis.py`, `membership.py`, `experimental.py`, originally developed by James Power.

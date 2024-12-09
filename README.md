# aidi_mlp_stock_market_prediction_lstm_dl_model

This repository contains a college project focused on predicting stock market movement patterns using machine learning, specifically Long Short-Term Memory (LSTM) models. The project aims to analyze historical stock data to predict future price movements, leveraging the sequential processing strength of LSTMs.

## Instructions for running the Research papers model

1. Use the file Deep_Learning_Model_Rerun_Sherif_O.ipynb
2. Uncomment the neccesary pip install line in the first cell based on the OS and CPU architecture you are use.
3. Also, you will need to install Graphviz to get the diagrams if needed. The link to installation instruction is in the first cell of the notebook.
4. After all the libraries and software has been installed, run each IPython notebook cell by cell to reproduce the research paper's results.

## Instructions for running the LightGBM model

1. Create a virtual environment with Python=3.8.6
2. Pip install the requirements_lightgbm.txt file
3. Install libomp:
    1. On MacOs use 'brew install libomp'
    2. On Linux use 'sudo apt install libomp-dev' on debian. If using other Linux flavours use their respective package managers.
4. After installation is complete, run each cell in the light_gbm_model.ipynb notebook sequentially to get the results.

## Instructions for running Random Forest and Decision Tree Regressor model
1. run the command below:
   - pip install pandas numpy scikit-learn matplotlib
2. run each cell in the Random_Forest_and_Decision_Tree.ipynb notebook sequentially to get the results

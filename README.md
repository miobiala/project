# Msc-Project-Code

This repository contains the source code for my Msc Project on "What impact do sentiment indicators have in stock analysis and identifying trading signals"
it is optimised for the use with Google Colab and mounts the Google Drive to Load required folders to Colab notebooks.
The stock data was automatically loaded from yfinance but importing the yfinance tool in my colab notebook.
The Project consists of showing the how well the RNN model predicts stock movement with the addition of sentiment indicators. 

# Content of folders
## Stock_code
this is the first verision of code where i tested the RNN model on stock data without sentiment indicators.
## Stock_code_v2
this is the second version where I compared other machine learning models to see which trains best with in the inclusion of sentiment indicator VIX
## Final Code
This is where I implemented my hyperparameter tuning to select the best parameters for my RNN model and visualized the actual vs predicted stock prices to show possible trading signals

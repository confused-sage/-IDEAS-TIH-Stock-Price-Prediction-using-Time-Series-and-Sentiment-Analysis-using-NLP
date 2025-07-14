# Stock Price Movement Prediction using Time Series Forecasting and Sentiment Analysis

This project was developed as part of the **IDEAS-TIH Summer Internship 2025** at **ISI Kolkata**.


## Overview

The objective of this project is to predict short-term stock price movements using a hybrid approach that combines:

- **Time Series Forecasting Models** (LSTM, Transformer)
- **Sentiment Analysis** using NLP on financial news headlines
- Multimodal fusion and ensemble learning (LSTM + Transformer along with XGBoost Classifier)

## Dataset

You can access the dataset via Mega:

🔗 [Download Dataset from Mega](https://mega.nz/folder/vRtQRDBJ#srbMPtX8lV8rLMDQo1nq-A)

>Please download the folder and place it inside the root of the project directory as:  

> `./data/`

## How to Run

1. **Clone the repository**:
   ```
   git clone https://github.com/confused-sage/-IDEAS-TIH-Stock-Price-Prediction-using-Time-Series-and-Sentiment-Analysis-using-NLP.git
   ```
2. **Install dependencies**:
```
pip install -r requirements.txt
```
3. **Prepare the dataset**:

- Download the dataset from the Mega link

- Extract the contents and place the data/ folder inside the project directory.

4. **Run the Baseline Models**:

Once the `./data/` is setup properly, Open the `5. Baseline Modelling.ipynb` and run the Jupyter Notebook cells.

5. **Run the Hybrid Model**:

Once the `./data/` is setup properly, Open the `6. Advanced Modelling.ipynb` and run the Jupyter Notebook cells.
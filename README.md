# Laptop Price Predictor

A machine learning project that predicts laptop prices based on specifications using various ML algorithms.

## Features
- Data preprocessing
- Feature engineering
- Linear Regression model
- Streamlit web interface

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit

## Project Structure

```
Laptop-Price-Prediction
│
├── app.py
├── requirements.txt
├── setup.sh
├── README.md
│
├── data
│   └── laptop_data.csv
│
├── models
│   ├── pipe.pkl
│   └── df.pkl
│
├── notebooks
│   └── Laptop_prediction.ipynb
│
└── images
    ├── home_page.png
    └── prediction_result.png
```

## How to Run

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

## Application Demo

![Laptop Price Predictor](Image/Screenshot%20(18).png)
![Prediction](Image/Screenshot%20(19).png)

## Project Overview

This project predicts laptop prices based on specifications such as RAM, processor, GPU, storage, and brand using a various ML algorithms.


## Future Improvements

- Add Random Forest model
- Add Gradient Boosting
- Improve feature engineering
- Deploy the project online

## Author

Ayush Sawant  
AI & Data Science Student
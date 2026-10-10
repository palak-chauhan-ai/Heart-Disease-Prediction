# Heart Disease Prediction Using Machine Learning

## About the Project
This project is a machine learning-based application that predicts the likelihood of heart disease using selected health parameters. It uses a trained K-Nearest Neighbors (KNN) model and a Streamlit web interface to provide predictions based on user inputs.

## Features
- Interactive Streamlit web application
- Trained KNN machine learning model
- Data scaling using a saved scaler
- Consistent input feature ordering
- Instant prediction results

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit

## Project Structure
- `app.py` — Streamlit application
- `Heart_Disease.ipynb` — Jupyter Notebook containing the ML code
- `knn_heart_model.pkl` — Saved KNN model
- `heart_scaler.pkl` — Saved scaler
- `heart_columns.pkl` — Saved feature columns
- `requirements.txt` — Required Python libraries

## How to Run Locally

**1. Install the required libraries**
```bash
pip install -r requirements.txt
```

**2. Run the Streamlit application**
```bash
streamlit run app.py
```

## Disclaimer
This project is developed for educational purposes only. Its predictions are experimental estimates and must not be considered a medical diagnosis or a substitute for advice from a qualified healthcare professional.

## Author
Palak Chauhan

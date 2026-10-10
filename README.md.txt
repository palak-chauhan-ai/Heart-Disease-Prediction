# Heart Disease Prediction Using Machine Learning

## About the Project
This project uses Machine Learning to predict the likelihood of heart disease based on selected health parameters. It includes a trained K-Nearest Neighbors (KNN) model and a Streamlit web application that allows users to enter health information and view a prediction.

## Features
- Interactive Streamlit web application
- Trained KNN machine learning model
- Input preprocessing using a saved scaler
- Consistent feature ordering
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
- `Heart_Disease.ipynb` — Jupyter Notebook containing model development
- `knn_heart_model.pkl` — Saved KNN model
- `heart_scaler.pkl` — Saved feature scaler
- `heart_columns.pkl` — Saved model input columns
- `requirements.txt` — Required Python libraries

## How to Run the Project

1. Install Python.
2. Open a terminal in the project folder.
3. Install the required libraries:

   `pip install -r requirements.txt`

4. Start the Streamlit application:

   `streamlit run app.py`

## Disclaimer
This project is developed for educational purposes only. Its predictions are experimental estimates and should not be used as a medical diagnosis or as a substitute for advice from a qualified healthcare professional.
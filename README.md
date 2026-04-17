# Breast Cancer Detection App

This is a machine learning web application built with Streamlit that predicts whether a breast tumor is benign or malignant (cancerous) based on cell nucleus characteristics.

## Features
- Interactive UI to input 30 different mean, standard error, and worst dimension features of a cell nucleus.
- Uses a pre-trained Support Vector Classifier (SVC) model (`svc.joblib`) for predictions.
- Instantly predicts and displays the result (Cancer / Not Cancer).

## Files in the Repository
- `app.py`: The main Streamlit application script.
- `svc.joblib`: The pre-trained Support Vector Machine model.
- `requirement.txt`: The list of Python dependencies required to run the app.

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd Machine_learning
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirement.txt
   ```

3. Run the Streamlit application:
   ```bash
   python -m streamlit run app.py
   ```

4. The app will open in your default web browser at `http://localhost:8501`.

# Iris Classification REST API Using FastAPI

## Aim

To develop, test and document a REST API using FastAPI for serving predictions from a trained machine learning model.

## Technologies Used

- Python
- FastAPI
- Scikit-learn
- NumPy
- Joblib
- Pytest
- HTTPX

## Machine Learning Model

The Iris dataset is used for classification. A Random Forest Classifier with 100 estimators and random_state 42 is trained and saved as a Joblib artifact.

The trained model is stored at:

artifacts/iris_model.joblib

## Project Structure

FASTAPI_5/
- artifacts/iris_model.joblib
- tests/test_api.py
- main.py
- model.py
- requirements.txt
- README.md

## Installation

Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
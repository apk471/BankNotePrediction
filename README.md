# Banknote Authentication Model

This project aims to authenticate banknotes using machine learning techniques. The dataset used for training the model is obtained from Kaggle, and the authentication functionality is integrated using FastAPI.

## Dataset

Dataset Source: [Kaggle Banknote Authentication Dataset](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data)

## Model

The machine learning model is trained using the banknote authentication dataset. Various classification algorithms are experimented with to find the most suitable one for this task. Once trained, the model can predict whether a given banknote is authentic or counterfeit with high accuracy.

## Integration with FastAPI

FastAPI is used to integrate the banknote authentication model into a web service. FastAPI provides a simple and efficient way to create APIs with Python. The model is wrapped into an API endpoint, allowing users to authenticate banknotes by sending their images to the API.

## Usage

To use the banknote authentication model:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the FastAPI server using `uvicorn main:app --reload`.
4. Send POST requests to the `/predict` endpoint with banknote images to authenticate them.

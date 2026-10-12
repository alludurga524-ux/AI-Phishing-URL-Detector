# AI Phishing URL Detector

## Project Overview
An AI-based web application that analyzes URL patterns and predicts whether a URL may be phishing or legitimate.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Random Forest Classifier
- Google Colab
- Gradio

## Features
- Accepts a URL as input.
- Extracts URL-based features.
- Predicts whether a URL may be phishing or legitimate.
- Displays the prediction and model confidence.

## Model
A Random Forest Classifier trained using URL-based features.

## How to Run
1. Open the project notebook in Google Colab.
2. Install the required libraries.
3. Load the trained model.
4. Run the feature extraction and prediction functions.
5. Launch the Gradio interface.

## Disclaimer
Predictions are estimates, not guarantees. A legitimate prediction does not prove a website is safe. Do not enter sensitive information based only on this tool's prediction.

## Download the Trained Model

The trained Random Forest model is available on Google Drive.

[Download the model](https://drive.google.com/file/d/1cdbjN4DHI2rs0wkhNta8lTd165klcOCs/view?usp=sharing)

After downloading, place `phishing_url_detector_consistent.joblib` in the location expected by the notebook.

## Disclaimer

This is an educational phishing-detection prototype. Predictions are estimates and do not guarantee that a website is safe or malicious.





# Health Care Disease Prediction Web Application

This is a Flask-based web application that predicts various diseases using machine learning models. The project includes modules for:

- **Kidney Disease Prediction (KYD)**
- **Brain Tumor Detection (KYH)**
- **Heart Disease Prediction**
- **Liver Disease Prediction**
- *Can be developed in future

---

## Features

- Predict diseases based on user input symptoms or medical parameters.
- Upload images for brain tumor detection.
- Interactive web UI built using Flask and HTML templates.
- Models are pre-trained using datasets and loaded at runtime.
- Provides disease description, precautions, medication, diet, and workout suggestions.

---

## Project Structure

- `app.py` - Flask application script handling routes and predictions.
- `Disease_Prediction.py` - Kidney disease prediction logic.
- `heart.py` - Heart disease model training and prediction functions.
- `liver.py` - Liver disease model training and prediction.
- `static/` - Contains static files like images.
- `templates/` - HTML templates for rendering web pages.

---

## Usage

1. Clone the repository.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt

## Run the Flask app:
   python app.py
   
Open your browser and visit http://127.0.0.1:5000/ to use the application.

## Technologies Used

- Python 3.x
- Flask
- TensorFlow / Keras (for brain tumor detection model)
- scikit-learn (for disease prediction models)
- HTML/CSS (for frontend)



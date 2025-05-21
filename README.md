Health Care Disease Prediction Web Application
This is a Flask-based web application that predicts various diseases using machine learning models. The project includes modules for:

Kidney Disease Prediction (KYD)

Brain Tumor Detection (KYH)

Heart Disease Prediction

Liver Disease Prediction

(Optional) Lung Cancer Prediction (commented out in code)

Features
Predict diseases based on user input symptoms or medical parameters.

Upload images for brain tumor detection.

Interactive web UI built using Flask and HTML templates.

Models are pre-trained using datasets and loaded at runtime.

Provides disease description, precautions, medication, diet, and workout suggestions.

Project Structure
app.py - Flask application script handling routes and predictions.

Disease_Prediction.py - Kidney disease prediction logic.

heart.py - Heart disease model training and prediction functions.

liver.py - Liver disease model training and prediction.

static/ - Contains static files like images.

templates/ - HTML templates for rendering web pages.

Usage
Clone the repository.

Install required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and visit http://127.0.0.1:5000/ to use the application.

Routes Overview
/ - Home page.

/kyd - Kidney disease prediction input page.

/predict - Process symptoms and show kidney disease prediction.

/kyh_diseases - Brain tumor detection home.

/upload - Upload brain MRI images for tumor prediction.

/heart - Heart disease prediction form.

/heart_predict - Process heart disease prediction.

/liver - Liver disease prediction form.

/liver_predict - Process liver disease prediction.

/request_appointment - Appointment request page.

/about - About the project.

/contact - Contact information.

Technologies Used
Python 3.x

Flask

TensorFlow / Keras (for brain tumor detection model)

scikit-learn (for disease prediction models)

HTML/CSS (for frontend)

Notes
Some models like lung cancer prediction are currently commented out.

Make sure to provide the necessary trained model files in the project.

This is a demo app and should be further enhanced for production use.

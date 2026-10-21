Liver Tumor Detection and Segmentation

## Project Overview
This project detects and segments **liver tumors** from medical imaging data using a web-based application built with **Django**. 
The application integrates trained machine learning weights to process scans, perform segmentation, and display predictions through an interactive user interface.

## Technologies Used
- Python
- Django (Web Framework)
- TensorFlow / Keras / OpenCV
- SQLite
- HTML, CSS, JavaScript

## Project Workflow
1. Dataset Preparation & Preprocessing (Medical imaging scans and arrays)
2. Model Integration (Loading trained deep learning weights)
3. Backend Processing (Handling image uploads via Django views and forms)
4. Tumor Segmentation & Prediction
5. Results Rendering on an Interactive UI
6. Testing with sample medical scans

## How to Run

### 1. Install Dependencies
pip install -r requirements.txt

### 2. Apply Database Migrations
python manage.py migrate


### 3. Run the Development Server
python manage.py runserver
*(Or use the provided `run.bat` script on Windows)*

### 4. Access the App
Open your browser and navigate to:
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

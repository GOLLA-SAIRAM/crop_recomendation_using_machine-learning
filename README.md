# CROP RECOMMENDATION SYSTEM USING MACHINE LEARNING

## Project Overview

The Crop Recommendation System is a web-based application that predicts the most suitable crop to grow based on various environmental factors and soil nutrient content. The application leverages a machine learning model trained on historical agricultural data and provides recommendations by inputting the following parameters:

### **Nitrogen (N):** Nutrient essential for plant growth.  
### **Phosphorus (P):** Helps with the energy transfer in plants.  
### **Potassium (K):** Important for overall plant health.  
### **Temperature:** Measured in Celsius, crucial for plant metabolic processes.  
### **Humidity:** Important for transpiration and water absorption.  
### **pH:** Measures soil acidity/alkalinity, critical for nutrient availability.  
### **Rainfall:** Amount of precipitation that can affect water availability for crops.  

Based on these inputs, the model predicts the crop best suited for these conditions from a predefined set of crops, including rice, maize, apple, banana, etc.

## Technologies Used

### **Flask:** Used to create the web application and handle HTTP requests.  
### **Pandas:** For data manipulation and processing.  
### **NumPy:** For efficient numerical computation.  
### **Scikit-learn:** For training and implementing the machine learning model.  
### **Gunicorn:** Used to deploy the Flask app in a production environment.  

## Project Files

- **app.py:** The Flask application that handles the web interface and model predictions.
- **index.html:** The frontend HTML file where users input soil and environmental conditions.
- **new_rf_model.joblib:** The saved machine learning model (**RandomForestClassifier**) used for predictions.
- **features_data.joblib:** The file containing feature information used for prediction input.
- **requirements.txt:** Contains the dependencies required for the project.
- **wsgi.py:** The entry point for running the Flask app with **Gunicorn**.
running the Flask app with Gunicorn.

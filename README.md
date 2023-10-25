# Property Value Estimator
This repository contains a project that predicts home prices in Bangalore using machine learning.

The project is divided into three components:

## Machine Learning Model (Python, Scikit-Learn):
- I first built a predictive model using Scikit-Learn's Linear Regression.
- The model was trained on the Bangalore home prices dataset obtained from Kaggle.com.
- The dataset was used to train the model to predict home prices based on features such as square feet, the number of bedrooms, and the number of baths.

## Python Flask Server:
- The second step involved creating a Python Flask server.
- This server utilized the saved machine learning model to serve HTTP requests.
- When a client made an HTTP request with features like square feet, location, the number of baths, and the number of bedrooms, the Flask server used the model to predict the home price and returned the result as a response.

## Web Application (HTML, CSS, JavaScript):
- The third component of this project was a web application built using HTML, CSS, and JavaScript.
- Users were able to interact with the model through this web interface.
- They could input property details such as square footage and the number of bedrooms, and the web application made requests to the Python Flask server to retrieve the predicted home price.

# Demo:
<img width="1392" alt="Screenshot 2023-10-25 at 3 25 35 PM" src="https://github.com/naveedeveloper/property-value-estimator/assets/64096661/22439d21-515b-4853-b750-8721cbed1bc2">
<img width="1392" alt="Screenshot 2023-10-25 at 3 25 48 PM" src="https://github.com/naveedeveloper/property-value-estimator/assets/64096661/dda8f86d-d9e9-49ca-94bc-a6f1cd3f9e65">
<img width="1392" alt="Screenshot 2023-10-25 at 3 26 21 PM" src="https://github.com/naveedeveloper/property-value-estimator/assets/64096661/1a660c69-0fb0-45f6-aa9d-1c2b878b48b0">
<img width="1392" alt="Screenshot 2023-10-25 at 3 26 27 PM" src="https://github.com/naveedeveloper/property-value-estimator/assets/64096661/d02b70af-bcfd-4aa4-a3ae-bb91914d99fb">




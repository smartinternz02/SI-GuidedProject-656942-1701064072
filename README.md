# OptiCrop: Smart Agricultural Production Optimization Engine
OptiCrop is a data-driven software system that helps optimize agricultural production by leveraging environmental factors and machine learning techniques. By analyzing key environmental variables such as Nitrogen (N), Phosphorous (P), Potassium (K) levels, soil temperature, humidity, pH, rainfall, and crop types, OptiCrop provides actionable insights to farmers for improving crop yields and resource utilization.

# Project Description
The OptiCrop project aims to improve agricultural practices by using machine learning to provide intelligent crop production recommendations. By analyzing various environmental factors and crop characteristics, OptiCrop optimizes the resource usage (water, fertilizer, etc.) and increases crop yields.



![image](https://github.com/user-attachments/assets/0fcf8ca9-b264-4047-91cd-0c014352a43a)



# Key Features:
Smart Recommendations: Suggests optimal production practices based on environmental conditions.
Data-Driven Insights: Uses historical and current data to forecast crop yields and recommend best practices.
Sustainability Focus: Aims to maximize productivity while minimizing resource wastage and environmental impact.
Farmer Friendly: A web application that provides an easy-to-use interface for farmers to input their data and receive actionable recommendations.
The system is designed for farmers, agricultural researchers, and policymakers to help maximize yields in an environmentally sustainable manner.

# Objective
Optimize Crop Yields: Maximize the productivity of crops by analyzing environmental and soil factors.
Efficient Resource Utilization: Recommend optimal usage of resources such as water, fertilizers, and pesticides based on data.
Sustainability: Minimize environmental impact by providing resource-efficient farming practices.
Machine Learning Models: Apply classification and regression models to predict crop yields and optimize farming practices.
Web Interface: Develop an easy-to-use Flask web application for farmers to interact with the system.
# Data Description
The dataset used in this project includes various environmental and crop-specific factors:

Environmental Factors:
Nitrogen (N), Phosphorous (P), Potassium (K) levels.
Soil temperature, humidity, and pH.
Rainfall and other weather-related parameters.
Crop Information:
Different types of crops (e.g., wheat, maize, rice, etc.)
Associated crop-specific requirements.
The data is collected from various agricultural regions and is used to train machine learning models that provide crop-specific recommendations.

# Machine Learning Models Used
We will be using the following machine learning algorithms for this project:

K-Nearest Neighbors (KNN): A classification algorithm used to predict the class of a given crop based on environmental factors.

K-Means Clustering: An unsupervised learning algorithm used to group similar crops together based on environmental conditions.

Logistic Regression: A classification algorithm used to predict whether a given set of environmental conditions will be favorable for a specific crop or not.

The model will be trained on the available dataset, and after testing, the best-performing model will be selected and saved in a .pkl file for further use.

# Technical Architecture
Data Preprocessing:
Cleaning and preprocessing of raw data (handling missing values, normalization, encoding categorical features).
Feature engineering to derive new attributes (e.g., interactions between environmental factors).
Model Training:
Training KNN, K-Means, and Logistic Regression models.
Evaluation of models using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
Web Application:
Flask integration for building a web application that allows farmers to input environmental data and receive crop recommendations.
Deployment:
The model will be saved in a .pkl file and deployed on IBM Cloud for easy access and use.
# System Flow:
User Inputs: The farmer enters environmental and soil data (e.g., NPK levels, soil temperature, rainfall, etc.) into the web application.
Model Prediction: The system uses the trained machine learning model to predict the best crops to plant under the given conditions.
Output: The system provides recommendations and insights, such as crop type, expected yield, and resource utilization.
# Installation
To set up the project on your local machine, follow these steps:

# Prerequisites
Python 3.x: Ensure Python 3 is installed.
Required Libraries: Use requirements.txt to install the necessary libraries.
# Steps
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/OptiCrop.git
Navigate to the project directory:

bash
Copy code
cd OptiCrop
Create a virtual environment:

bash
Copy code
python -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
# Usage
Data Preprocessing: Run the data_preprocessing.py script to clean and prepare the data.

Model Training:

Train the models using the train_models.py script.
Evaluate the performance of the models using evaluate_models.py.
Flask Web App:

To start the Flask web app:
bash
Copy code
python app.py
Visit http://127.0.0.1:5000/ on your browser to access the web interface.
Model Saving:

After training, the best model will be saved in a .pkl file. This file can be used for predictions in the Flask app.
# Technologies
Python: Programming language used for data analysis, machine learning, and web app development.
Flask: A micro web framework used to create the web application.
Scikit-learn: For machine learning models such as KNN, Logistic Regression, and K-Means.
Pandas: For data manipulation and preprocessing.
NumPy: For numerical operations and array manipulations.
Matplotlib / Seaborn: For data visualization and performance evaluation.
IBM Cloud: For deploying the Flask app and machine learning model.
# Deployment
Once the Flask application is tested locally, you can deploy it on IBM Cloud or another cloud platform for production use. Follow the instructions in the deployment/README.md for deployment details.

# Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -am 'Add new feature').
Push to your branch (git push origin feature-name).
Open a pull request.
# License
This project is licensed under the MIT License.

# Contact
For any questions or feedback, feel free to contact:

Email: nikhilt1120@gmail.com.com
GitHub: https://github.com/Nikhil1120
# Acknowledgements
Thanks to the agricultural datasets and open-source tools that made this project possible.
Special thanks to the data science and AI community for the inspiration and support in implementing this project.

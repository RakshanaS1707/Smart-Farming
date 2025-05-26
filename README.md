# A Decision Support System for Smart Farming and Sustainable Agricultural Practices

## Overview

This project aims to enhance farming efficiency by integrating modern technology and data analytics. The decision support system leverages machine learning models and real-time weather data to provide actionable insights for disease detection, crop management, and sustainable farming. By optimizing resource utilization and providing accurate crop forecasts, the system helps improve overall productivity while minimizing environmental impact.

## Key Features

- **Disease Detection**: Utilizes image processing and Convolutional Neural Networks (CNNs) to identify and classify plant diseases.
- **Crop Recommendation**: Provides recommendations based on soil and climate data to ensure optimal crop growth.
- **Weather-Based Crop Protection**: Integrates real-time weather data to predict disease outbreaks and recommend preventive measures.
- **Fertilizer Calculator**: Suggests the appropriate amount of fertilizer based on crop and soil data.

## Project Structure

- **/backend**: FastAPI and Flask code for serving predictions, recommendations, and integrating weather APIs.
- **/data**: Contains sample datasets for testing, training, and validation.
- **/frontend**: React-based frontend for user interactions, including image uploads and viewing results.
- **/model_training**: Jupyter notebooks and scripts for training and evaluating the machine learning models.
- **/models**: Pre-trained models (e.g., CNN for disease detection, Random Forest for crop recommendations).


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/prudhiv17/Smart-Farming.git
   cd repo-name
   ```

2. Navigate to the backend directory:
   ```bash
   cd backend
   ```

3. Install the required dependencies for the backend:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```

5. Navigate to the frontend directory and install dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

6. Start the React app:
   ```bash
   npm start
   ```

## Dependencies

- **Backend**: FastAPI,Flask, NodeJS
- **Frontend**: ReactJS, Axios
- **Database**: MongoDB
- **Weather API**: OpenWeatherMap API for real-time weather data
- **Other Libraries**: OpenWeatherMap API, PIL (Python Imaging Library) , Scikit-learn, TensorFlow, OpenCV, NumPy, Pandas, Matplotlib for data manipulation and visualization


## Dataset

- **Plant Disease Dataset**: The system uses plant disease images from the `Plant_Village` dataset.
- **Weather Data**: Weather information is retrieved using the OpenWeatherMap API.
- **Crop Recommendation Data**: The crop recommendation system is trained using data from the `crop_recommendation` dataset on Kaggle.

## Usage

To utilize the system, start by uploading plant images through the React frontend to receive disease detection results from the CNN model. For crop recommendations, input soil and climate data to get tailored suggestions based on the Random Forest model. For weather-based crop protection, either input real-time weather data or automatically fetch it to receive suggestions for crop protection strategies. Additionally, the fertilizer calculator can be used to determine optimal fertilizer usage based on specific crop and soil characteristics. Ensure all required data, such as weather and soil data, is available before running the system.

##Output
![image](https://github.com/user-attachments/assets/e3d646b2-169d-4124-b462-ccb1e1ec87dd)
Disease Detection
![image](https://github.com/user-attachments/assets/b4bd4c14-196f-4a12-a57b-8be22fff8f06)
Crop Recommendation
![image](https://github.com/user-attachments/assets/8410708e-26c2-4cc3-8b35-30da03a191da)
Weather Based Disease Prevention
![image](https://github.com/user-attachments/assets/7a71ae6c-d685-4ef2-a355-7e6f8eee4ef8)
Fertilizer Calculator
![image](https://github.com/user-attachments/assets/759fc1f3-8271-409a-9042-d6bb59c45371)
![image](https://github.com/user-attachments/assets/9afcc127-26fd-428e-9a6a-01225d3aa91b)
RESULT OF THIS APPLICATION
![image](https://github.com/user-attachments/assets/5b24f25e-a71b-4d11-9948-4f3afc7e3abe)
![image](https://github.com/user-attachments/assets/cd7d7c70-4b15-4ce4-a7b5-6b8faef42d37)
![image](https://github.com/user-attachments/assets/92d23602-3990-4616-a076-3be12a88492f)
![image](https://github.com/user-attachments/assets/a1375c7d-92c1-4bef-afc1-d6bbc342dd1f)
Sample images of potato healthy and disease leaf 
![image](https://github.com/user-attachments/assets/dc722bbf-e060-4e46-af7e-b5c9893b3504)






# Property Loan Approval App

## Overview

Welcome to the Property Loan Approval App repository! This project combines machine learning and app development to create a web application that predicts loan approval for property loans. The app is built using Streamlit, and the machine learning model is based on the RandomForestClassifier from scikit-learn.

## Project Structure

The project is structured into several components, showcasing a comprehensive understanding of data science and web application development.

### 1. Data Preparation and Exploration

- **Dataset:** The project begins with loading and cleaning the dataset from a CSV file containing property loan data. Data preprocessing techniques are applied to handle missing values, convert categorical variables, and ensure data consistency.
- **Exploratory Data Analysis (EDA):** Gain insights into the dataset through EDA, leading to informed decisions during feature selection and engineering.

### 2. Model Training

- **Algorithm Selection:** The RandomForestClassifier from scikit-learn is chosen for loan approval prediction. The model is trained on a carefully split dataset, and feature scaling and one-hot encoding are applied through pipelines for efficient preprocessing.

### 3. Streamlit Web App

- **User Interface:** The core of the project is an interactive web application created using Streamlit. The app features a user-friendly interface with a sidebar for entering applicant details, loan amount, and credit history.
- **Real-time Predictions:** A "Predict" button triggers the machine learning model, providing instant loan approval predictions based on user input.

### 4. Technical Details

- **Data Preprocessing:** Utilized scikit-learn's pipelines to handle numerical and categorical data separately, ensuring efficient and reproducible preprocessing steps.
- **Model Selection:** The RandomForestClassifier was chosen for its ability to handle both numerical and categorical features, providing a robust solution for the binary classification task.
- **Web App Development:** Employed Streamlit for building a responsive and interactive web application, integrating user input fields, a prediction button, and result display.
- **Model Deployment:** Saved the trained model using joblib for later deployment, enabling real-time predictions within the Streamlit app.

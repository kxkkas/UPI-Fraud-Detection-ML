# UPI Fraud Transaction Detection Using Machine Learning

## 📌 Project Overview

This project is a machine learning-based **UPI Fraud Transaction Detection System** designed to identify potentially fraudulent transactions in digital payment data.

The system combines data preprocessing, feature analysis, machine learning, and a web-based application to analyze transaction information and classify transactions based on their likelihood of being fraudulent.

## 🎯 Objectives

* Detect potentially fraudulent UPI transactions.
* Analyze transaction patterns and user behavior.
* Preprocess and transform transaction data for machine learning.
* Train a classification model for fraud detection.
* Integrate the trained model into a web application.
* Provide an easy-to-use interface for fraud prediction.

## 🛠️ Technologies Used

* Python
* Django
* Pandas
* NumPy
* Scikit-learn
* SQLite
* HTML
* CSS
* Machine Learning
* Data Preprocessing

## 🤖 Machine Learning Workflow

The project follows a typical machine learning pipeline:

1. Collect and prepare transaction data.
2. Clean and preprocess the dataset.
3. Perform feature engineering.
4. Prepare the data for model training.
5. Train the machine learning model.
6. Evaluate the model.
7. Save the trained model.
8. Integrate the model with the web application.
9. Generate fraud predictions for transactions.

## 📂 Project Structure

```text
UPI-Fraud-Detection-ML/
│
├── Dataset/
│   └── Transaction datasets
│
├── Fraud/
│   └── Fraud detection application components
│
├── FraudApp/
│   └── Web application components
│
├── model/
│   └── Trained machine learning model
│
├── screen_shots/
│   └── Application screenshots
│
├── manage.py
├── train_model.py
├── requirements.txt
├── runWebServer.bat
└── database.txt
```

## 🔍 Key Features

* UPI transaction analysis
* Fraud transaction classification
* Machine learning-based prediction
* Data preprocessing and feature engineering
* Trained model integration
* Django-based web application
* SQLite database integration
* User-friendly fraud detection interface

## 🌐 Web Application

The trained machine learning model is integrated into a Django web application.

Users can provide transaction-related information through the application, and the system processes the input using the trained model to generate a fraud prediction.

## 📊 Dataset

The project uses transaction-related data containing features that can be used to identify patterns associated with fraudulent activity.

The dataset is processed before being passed to the machine learning model.

> **Note:** The dataset included in this repository is intended for project/demo purposes.

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/kxkkas/UPI-Fraud-Detection-ML.git
```

### 2. Navigate to the project

```bash
cd UPI-Fraud-Detection-ML
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Train the model

```bash
python train_model.py
```

### 5. Start the Django server

```bash
python manage.py runserver
```

Then open the local address provided by Django in your browser.

## 🖥️ Application Screenshots

Screenshots of the fraud detection application are available in the `screen_shots` folder.

## 🔮 Future Improvements

* Improve fraud detection performance with advanced ensemble models.
* Add real-time transaction monitoring.
* Implement additional fraud detection features.
* Add model performance dashboards.
* Integrate explainable AI for prediction analysis.
* Deploy the application to a cloud platform.
* Add real-time alerts for high-risk transactions.

## 👨‍💻 Author

**Kashif Khan**

M.Tech Computer Science | Data Science & AI/ML

GitHub: [kxkkas](https://github.com/kxkkas)

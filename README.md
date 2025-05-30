# Web-Project
Financial Transaction Fraud Detection System is a full-stack web application designed to identify fraudulent activities in various types of financial transactions. The platform features a clean and user-friendly interface that allows users to select the type of fraud detection they need: Online Payment Fraud, Credit Card Fraud, or E-Commerce Fraud.
Financial Transaction Fraud Detection System
This project is a user-friendly web application that detects financial fraud using machine learning. It allows users to choose from three fraud types and enter transaction details to check if a transaction is genuine or fraudulent.

🔍 Fraud Detection Types
Online Payment Fraud
Detects suspicious money transfers based on transaction type, amount, and account balances.

Credit Card Fraud
Identifies fraudulent card activity using card type, location, merchant info, and transaction time.

E-Commerce Fraud
Flags fake orders by analyzing product, amount, payment method, shipping address, and user history.

🌐 Features
Responsive Login Page for user access

Clean Dashboard to choose between fraud types

Separate HTML Pages for each fraud type with custom input fields

Real-time Prediction Output (when connected to backend)

Designed with HTML, CSS, and basic JavaScript

🧰 Tech Stack
Frontend: HTML5, CSS3

Backend (Planned): Python (Flask or Django)

ML Models: Trained with datasets (e.g., from Kaggle)

Deployment: Future plan to deploy on Heroku/Render

📁 Folder Structure
bash
Copy
Edit
/fraud-detector
├── index.html            # Login page
├── main.html             # Main dashboard
├── online-payment.html   # Online payment form
├── credit-card.html      # Credit card form
├── ecommerce.html        # E-commerce form
├── style.css             # Stylesheets
└── (backend, models folders to be added)
✅ Future Scope
Connect with trained ML models for live predictions

Store user input and results in a database

Add authentication and result history

Deploy the complete system online


🤖 Task 4: AI Chatbot & Bank Data Analysis System
📌 Project Overview

This project demonstrates the development of an AI-based chatbot system along with bank dataset analysis using Python in Google Colab.

The system is designed to simulate intelligent responses using predefined patterns (retrieval-based chatbot) and perform data analysis on real-world banking data to understand customer behavior.

🎯 Objectives
Develop an AI-powered chatbot using NLP techniques
Enable instant responses based on user queries
Analyze bank customer data using visualization techniques
Identify patterns in customer demographics and subscription behavior
Improve understanding of customer engagement in banking systems
🛠️ Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn (for chatbot logic / NLP)
JSON Dataset (Intent-based chatbot)
CSV Dataset (Bank dataset)
📂 Datasets Used
1. Chatbot Dataset
Format: JSON (Intent.json)
Contains:
Intents (tags)
User patterns
Bot responses

👉 Used for building a retrieval-based chatbot

2. Bank Dataset
File: bank-full.csv
Contains customer banking information such as:
Age
Job
Marital status
Education
Loan details
Subscription status

👉 Used for data visualization and customer analysis

🤖 Chatbot Features
Intent-based response system
Pattern matching using NLP (TF-IDF / similarity)
Instant response generation
Handles multiple user queries
Simple and lightweight retrieval-based model
📊 Data Analysis Features

The bank dataset was analyzed using 6 different visualizations:

📌 1. Subscription Count Graph

Shows how many customers subscribed to term deposits.

📌 2. Job Distribution

Displays customer occupation distribution.

📌 3. Age Distribution

Shows age pattern of bank customers.

📌 4. Marital Status Distribution

Pie chart representation of customer marital status.

📌 5. Education vs Subscription

Analyzes how education affects subscription decision.

📌 6. Correlation Heatmap

Shows relationships between numerical variables.

📈 Key Insights
Majority customers belong to working-age group (30–50 years)
Most customers are from admin and blue-collar jobs
Education level impacts subscription rate
Married customers form the largest group
Strong patterns exist between financial features and subscription outcome
🚀 Project Workflow
Load chatbot dataset (Intent.json)
Build NLP-based retrieval chatbot
Load bank dataset (CSV)
Perform data cleaning and preprocessing
Generate 6 visualizations
Analyze customer behavior patterns
Present insights for business decision-making
📊 Output Visualization Types
Bar Chart
Pie Chart
Histogram
Count Plot
Line/Category Analysis
Correlation Heatmap

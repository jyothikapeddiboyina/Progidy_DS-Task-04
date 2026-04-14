📊 Sentiment Analysis & Visualization on Social Media Data
📌 Project Overview

This project focuses on analyzing and visualizing sentiment patterns in social media data to understand public opinions and attitudes towards different topics or brands.

The goal is to classify text into sentiments such as Positive, Negative, Neutral, and Irrelevant, and derive meaningful insights using data visualization and machine learning techniques.

🔗 Dataset

Dataset used for this project:
👉 https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%204

⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
WordCloud

🧠 Workflow
1️⃣ Data Loading
Loaded dataset using Pandas
Fixed missing column names

2️⃣ Data Preprocessing
Removed null values
Cleaned text (removed URLs, mentions, special characters)
Converted text to lowercase

3️⃣ Feature Engineering
Used TF-IDF Vectorizer for text representation

4️⃣ Model Building
Applied Logistic Regression for classification
Split data into training and testing sets

5️⃣ Model Evaluation
Achieved accuracy of ~78%+
Evaluated using:
Accuracy Score
Confusion Matrix
Classification Report

6️⃣ Data Visualization
Sentiment distribution (Count Plot)
Pie Chart
Word Cloud

📊 Results & Insights
Majority of sentiments were Positive/Neutral
Text preprocessing significantly improved performance
TF-IDF performed better than basic count vectorization
Logistic Regression provided good baseline performance

📌 Future Improvements
Try advanced models (Naive Bayes, SVM, Deep Learning)
Hyperparameter tuning
Deploy as a web app using Flask/Streamlit
Real-time sentiment analysis using APIs

🙌 Acknowledgements
Thanks to Prodigy InfoTech for providing this task and dataset

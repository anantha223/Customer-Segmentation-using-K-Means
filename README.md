Dataset (Customer Personality Data)
        ↓
Data Preprocessing
(Missing Values, Cleaning, Encoding)
        ↓
Feature Engineering
(Age, Total Spending, Campaign Response)
        ↓
Feature Scaling
(StandardScaler)
        ↓
K-Means Clustering
(Elbow Method → Optimal K)
        ↓
Cluster Formation
(Customer Segments)
        ↓
Visualization & Insights
        ↓
Business Actions
(Targeted Marketing, Personalization)

**Customer Segmentation using K-Means Clustering**
**📌 Overview**

This project performs customer segmentation using K-Means Clustering to group customers based on their income, spending behavior, and campaign interactions. The goal is to help businesses understand customer patterns and design targeted marketing strategies.

**🎯 Problem Statement**

Businesses often treat all customers the same, leading to inefficient marketing.
This project aims to:

Identify distinct customer groups
Improve targeted marketing
Increase customer engagement and ROI
**📊 Dataset**
Customer Personality Analysis Dataset
Contains information about:
Income
Spending habits
Product purchases
Campaign responses
**⚙️ Approach**
1. Data Preprocessing
Handled missing values
Removed irrelevant columns
Converted categorical data into numerical format
2. Feature Engineering
Created Age from birth year
Calculated Total Spending across product categories
Aggregated Campaign Responses
3. Feature Scaling
Applied StandardScaler to normalize data for distance-based clustering
4. Clustering
Used K-Means algorithm
Determined optimal clusters using the Elbow Method
5. Visualization
Plotted clusters to analyze customer segments
**📈 Results**
Customers were segmented into meaningful groups such as:
High-value customers
Low engagement customers
Potential growth customers

These insights help in:

Personalized marketing
Customer retention strategies
Better business decision-making
**🚀 Features**
End-to-end ML pipeline
Real-world dataset
Feature engineering for better insights
Cluster visualization
Scalable for business use
**🛠️ Tech Stack**
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
▶️ How to Run
pip install -r requirements.txt
python main.py

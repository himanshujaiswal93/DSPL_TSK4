Customer Segmentation using K-Means Clustering
📘 Project Overview

This project aims to perform Customer Segmentation using the K-Means Clustering algorithm.
The goal is to group mall customers based on their Annual Income and Spending Score, helping businesses identify distinct customer types and develop targeted marketing strategies.

🗂️ Dataset

Dataset Name: Mall Customers Dataset
Source: Kaggle - Mall Customers

Attributes:

CustomerID: Unique ID assigned to each customer

Gender: Male or Female

Age: Customer’s age

Annual Income (k$): Income in thousands

Spending Score (1-100): Score assigned based on spending behavior

⚙️ Steps Performed

Data Loading & Cleaning

Handled missing and duplicate values

Verified data types and performed basic preprocessing

Exploratory Data Analysis (EDA)

Analyzed distributions of age, gender, and income

Visualized spending patterns using seaborn and matplotlib

Elbow Method

Determined the optimal number of clusters using the Elbow Curve

Found optimal k = 5 for customer segmentation

K-Means Clustering

Applied K-Means with 5 clusters

Assigned each customer to their respective cluster

Cluster Visualization

Visualized clusters on the basis of Annual Income and Spending Score

Used color-coded scatter plot for clarity

📊 Cluster Insights
Cluster	Age (avg)	Annual Income (avg)	Spending Score (avg)	Segment Description
0	~42	~55	~49	Middle-aged, average income & spending
1	~33	~86	~82	High income & high spending (Premium customers)
2	~25	~25	~79	Low income but high spending (Impulsive buyers)
3	~41	~88	~17	High income, low spending (Potential target group)
4	~45	~26	~21	Low income, low spending (Budget-conscious)
🧠 Business Insights

Cluster 1: Focus for premium offers & loyalty programs

Cluster 2: Engage with discounts & promotions

Cluster 3: Target for conversion strategies

Cluster 4: Maintain basic offers due to low spending capacity

Cluster 0: Represents the average customer base

🧰 Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🧾 Conclusion

The K-Means model effectively segmented customers into five distinct groups based on their income and spending patterns.
These insights can help businesses optimize marketing strategies, improve customer satisfaction, and enhance profitability.

👨‍💻 Author

Himanshu Jaiswal
Data Science & Machine Learning Intern @ DSPL Technologies
📧 Email: jaiswalaasish00@gmail.com

🔗 LinkedIn
 | GitHub
 

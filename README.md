\# Customer Segmentation Using Unsupervised Learning



\## 📊 Executive Summary



This project applies K-Means clustering to segment customers based on behavioral data.



Three distinct customer groups were identified, revealing important differences in usage patterns and churn risk. The analysis highlights a critical segment of high-value customers with a high likelihood of churn, representing a key opportunity for targeted retention strategies.



These insights can support data-driven marketing decisions aimed at improving customer engagement and maximizing business value.



\## 🎯 Business Problem



Understanding customer behavior is essential for designing effective marketing strategies.



The objective of this project is to identify groups of similar customers based on usage patterns, allowing the business to:



* Improve customer targeting
* Increase engagement
* Reduce churn



\## 📊 Dataset



The dataset contains customer information, including:



* Age
* Monthly Charges
* Tenure
* Usage Rate
* Support Tickets
* Churn



The data was used to identify behavioral patterns and segment customers into distinct groups.



\## ⚙️ Methodology



The project follows these main steps:



1. Data Loading and Initial Exploration
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing (Feature Selection and Scaling)
4. Clustering using K-Means
5. Model Evaluation (Elbow Method and Silhouette Score)
6. Cluster Interpretation and Business Insights



\## 📈 Results \& Insights



Three customer segments were identified:



* **Low Engagement Customers**

Low usage and low churn

* **High-Value and At-Risk Customers**

High usage and high churn (critical segment)

* **Moderate Customers**

Balanced behavior



\### Key Insight



High-value customers present the highest churn risk, indicating a strong opportunity for targeted retention strategies.



\## 💼 Business Recommendations



* Focus retention efforts on high-value customers at risk
* Develop engagement strategies for low-usage customers
* Apply upselling and cross-selling strategies to moderate customers



\## 🛠️ Technologies Used



* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib



\## 📂 Project Structure



customer-segmentation-ml/

│

├── data/

├── notebooks/

│ └── customer\_segmentation\_kmeans.ipynb

├── requirements.txt

└── README.md



\## ⚙️ How to Run the Project



\#### 1. Create a virtual environment

conda create --name customerseg python=3.13

\#### 2. Activate the environment

conda activate customerseg

\#### 3. Install dependencies

conda install pip

pip install -r requirements.txt

\#### 4. Run Jupyter Notebook

jupyter notebook



\## 📌 Conclusion



This project demonstrates how unsupervised learning techniques can be used to generate actionable business insights.



By identifying customer segments and analyzing churn behavior, the analysis provides a strong foundation for data-driven marketing strategies and customer retention initiatives.


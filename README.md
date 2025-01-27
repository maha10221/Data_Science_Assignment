# Zeotap-Data-Science-Assignment
# Assignment Tasks:
Task 1: Exploratory Data Analysis (EDA) and Business Insights
1. Perform EDA on the provided dataset.
2. Derive at least 5 business insights from the EDA.
○ Write these insights in short point-wise sentences (maximum 100 words per
insight).
Deliverables:
● A Jupyter Notebook/Python script containing your EDA code.
● A PDF report with business insights (maximum 500 words).

![category_sales](https://github.com/user-attachments/assets/28203f00-ec0a-4075-8877-e71eeac98497)
![customer_signup_trend](https://github.com/user-attachments/assets/d35d5ad5-584f-49c1-b7ca-25b47e17c11c)
![customer_transaction_distribution](https://github.com/user-attachments/assets/5c91b7e2-a179-4bb7-9a60-3cc4144a0fb8)
![monthly_sales_trend](https://github.com/user-attachments/assets/76e951e1-d933-4992-a5c5-c7187a0773a2)
![regional_sales](https://github.com/user-attachments/assets/d0e7717a-cd0d-4a02-ab24-74c39b06afa3)


Task 2: Lookalike Model
Build a Lookalike Model that takes a user's information as input and recommends 3 similar
customers based on their profile and transaction history. The model should:
● Use both customer and product information.
● Assign a similarity score to each recommended customer.
Deliverables:
● Give the top 3 lookalikes with there similarity scores for the first 20 customers
(CustomerID: C0001 - C0020) in Customers.csv. Form an “Lookalike.csv” which has
just one map: Map<cust_id, List<cust_id, score>>
● A Jupyter Notebook/Python script explaining your model development.
Evaluation Criteria:
● Model accuracy and logic.
● Quality of recommendations and similarity scores.


Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques. Use both profile information
(from Customers.csv) and transaction information (from Transactions.csv).
● You have the flexibility to choose any clustering algorithm and any number of clusters in
between(2 and 10)
● Calculate clustering metrics, including the DB Index(Evaluation will be done on this).
● Visualise your clusters using relevant plots.
Deliverables:
● A report on your clustering results, including:
○ The number of clusters formed.
○ DB Index value.
○ Other relevant clustering metrics.
● A Jupyter Notebook/Python script containing your clustering code.
Evaluation Criteria:
● Clustering logic and metrics.
● Visual representation of clusters.

![clustering_metrics](https://github.com/user-attachments/assets/5d8301b3-73b5-4a48-b9e4-fefbbdaff24f)




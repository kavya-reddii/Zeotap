Overview:
This project focuses on analyzing an eCommerce transactions dataset consisting of customer, product, and transaction details. The goal is to extract meaningful insights from the data, build predictive models, and offer business-driven recommendations for improving customer engagement and sales strategies.

Files:
Customers.csv - Contains customer details (CustomerID, Name, Region, SignupDate).
Products.csv - Contains product information (ProductID, Name, Category, Price).
Transactions.csv - Contains transaction data (TransactionID, CustomerID, ProductID, Quantity, TotalValue, Price).
Tasks:
Task 1: Exploratory Data Analysis (EDA) and Business Insights
Performed data cleaning and transformation.
Explored the dataset by visualizing and summarizing key aspects such as customer regions, product categories, and transaction totals.
Deriving actionable business insights such as:
High-spending customers are often concentrated in specific regions.
Popular product categories can guide future marketing strategies.
Certain customers are more frequent buyers, indicating loyalty.
Task 2: Lookalike Model
Built a lookalike model to recommend 3 similar customers based on their profile and transaction history.
Used customer features and transaction data to calculate similarity scores between customers.
The model helps businesses identify and target customers similar to their existing high-value ones, enhancing marketing campaigns.
Task 3: Customer Segmentation / Clustering
Applied K-Means clustering to segment customers into distinct groups based on their transaction behaviors and demographic details.
Analyzed the clusters and their characteristics, such as total spending and frequency of transactions.
Calculated the Davies-Bouldin index to evaluate the quality of the clustering.
The clustering results allow businesses to tailor marketing strategies to specific customer groups.
Key Insights:
Customer Behavior: Segmenting customers allows for personalized marketing campaigns that can boost conversion and retention.
Product Preferences: Understanding popular product categories can help in product stocking and promotional efforts.
Targeted Marketing: The lookalike model helps find potential customers who behave similarly to existing loyal ones, guiding future customer acquisition.
Requirements:
Python 3.x
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Instructions to Run:
Clone the repository to your local machine.
Install the required libraries using the command:
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebooks (EDA.ipynb, Lookalike.ipynb, and Clustering.ipynb) to see the detailed analysis and model development.
Conclusion:
This analysis provides valuable insights that businesses can leverage to optimize their marketing strategies, enhance product offerings, and target the right customers for growth. By applying clustering and predictive models, businesses can make informed decisions and improve customer engagement and sales.








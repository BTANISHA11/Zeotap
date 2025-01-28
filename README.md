# Zeotap

E-Commerce Transactions Analysis

Project Overview

This project involves analyzing an e-commerce transactions dataset to perform Exploratory Data Analysis (EDA), build a Lookalike Model, and conduct customer segmentation through clustering. The goal is to derive actionable insights, build predictive models, and segment customers effectively to improve business strategies.

Dataset Description

The project utilizes three CSV files:

Customers.csv:

CustomerID: Unique identifier for each customer.

CustomerName: Name of the customer.

Region: Continent where the customer resides.

SignupDate: Date when the customer signed up.

Products.csv:

ProductID: Unique identifier for each product.

ProductName: Name of the product.

Category: Product category.

Price: Product price in USD.

Transactions.csv:

TransactionID: Unique identifier for each transaction.

CustomerID: ID of the customer who made the transaction.

ProductID: ID of the product sold.

TransactionDate: Date of the transaction.

Quantity: Quantity of the product purchased.

TotalValue: Total value of the transaction.

Price: Price of the product sold.

Tasks

1. Exploratory Data Analysis (EDA)

Goal: Analyze the dataset to uncover patterns and insights.

Key Steps:

Merge datasets to create a unified view.

Generate visualizations such as bar plots for sales by region, top products, etc.

Provide business insights based on the analysis.

2. Lookalike Model

Goal: Recommend three similar customers for each user based on profile and transaction history.

Approach:

Use customer and product data to engineer features.

Compute cosine similarity to identify similar customers.

Save recommendations in a Lookalike.csv file.

3. Customer Segmentation (Clustering)

Goal: Segment customers into clusters using profile and transaction data.

Approach:

Standardize features for clustering.

Apply KMeans clustering algorithm.

Evaluate the clusters using the Davies-Bouldin Index.

Visualize the clusters and save results in a Clustering_Results.csv file.

How to Run

Environment Setup:

Install required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.

Place the datasets (Customers.csv, Products.csv, Transactions.csv) in the project directory.

Execution:

Run the Python script or Jupyter Notebook provided in the repository.

Outputs:

EDA visualizations.

Lookalike recommendations in Lookalike.csv.

Clustering results in Clustering_Results.csv.

Insights from EDA

Regional Insights: Certain regions contribute significantly more to sales, highlighting key market areas.

Top Products: A few products dominate sales, indicating popular items.

Customer Behavior: High variability in customer lifetime value across regions.

Category Preferences: Specific product categories are more popular.

Growth Opportunities: Uneven customer distribution suggests potential growth regions.

Requirements

Python 3.7+

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Results

EDA: Key business insights derived from visualizations.

Lookalike Model: Personalized recommendations for customers.

Clustering: Segmentation with a Davies-Bouldin Index of X.XX (replace with actual value).

Contributing

Feel free to fork the repository and contribute by submitting a pull request. For major changes, please open an issue to discuss your ideas.

License

This project is open-source and available under the MIT License.

Contact

For questions or feedback, please contact [Your Name] at [Your Email].

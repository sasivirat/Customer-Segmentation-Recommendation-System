🌐 Overview
This repository hosts a project that delves deep into the vibrant sector of online retail, focusing on a dataset from a UK-based retailer available at the UCI Machine Learning Repository. This dataset includes all transactions occurring between 2010 and 2011, providing a rich ground for developing powerful customer segmentation and recommendation systems to enhance marketing strategies and boost sales.

🌟 Problem
In this project, we aim to transform transactional data into a customer-centric dataset by creating new features that will facilitate the segmentation of customers into distinct groups using the K-means clustering algorithm. This segmentation will allow us to understand the unique profiles and preferences of various customer groups, thus amplifying the efficiency of marketing strategies and fostering increased sales. Subsequently, we intend to develop a recommendation system that suggests top-selling products to customers within each segment who haven't purchased those items yet, enhancing marketing efficacy and fostering increased sales.

🎯 Objectives
The objectives of the project are as follows:

Data Cleaning & Transformation: Undertake data cleaning by handling missing values, duplicates, and outliers to prepare the dataset for effective clustering.
Feature Engineering: Develop new features based on the transactional data to create a customer-centric dataset, setting the stage for customer segmentation.
Data Preprocessing: Conduct feature scaling and dimensionality reduction to streamline data, enhancing the efficiency of the clustering process.
Customer Segmentation using K-Means Clustering: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.
Cluster Analysis & Evaluation: Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed.
Recommendation System: Develop a system to recommend best-selling products to customers within the same cluster who haven't purchased those products, aiming to enhance sales and marketing effectiveness.
📚 Dataset Description
The dataset comprises various metrics related to online retail transactions. The features of the dataset are described in the table below:

Variable	Description
InvoiceNo	Code representing each unique transaction. If this code starts with the letter 'c', it indicates a cancellation.
StockCode	Code uniquely assigned to each distinct product.
Description	Description of each product.
Quantity	The number of units of a product in a transaction.
InvoiceDate	The date and time of the transaction.
UnitPrice	The unit price of the product in sterling.
CustomerID	Identifier uniquely assigned to each customer.
Country	The country of the customer.
📁 File Descriptions
📓 Retail_Customer_Segmentation_Recommendation_System.ipynb: Jupyter notebook containing data exploration, visualization, modeling, and evaluation code.
📁 Online_Retail.csv: CSV file containing the online retail dataset.
📘 README.md: This file, providing an overview of the project.
🚀 Instructions for Local Execution
Clone this Repository: Begin by cloning this repository to your local setup.
Open the Notebook: Access the Retail_Customer_Segmentation_Recommendation_System.ipynb in Jupyter.
Install Dependencies: Ensure all necessary Python libraries are installed for seamless execution.
Execution: Run all cells in the notebook to witness the results and insights.

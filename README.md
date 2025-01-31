# Amazon-Black-Friday-Sales
Project Overview
This project leverages Amazon's electronics reviews dataset to analyze pricing trends, customer sentiments, and product performance during Thanksgiving and Black Friday. The goal is to optimize sales strategies through data-driven insights.

Objectives
Identify high-performing electronics products for Black Friday.
Analyze price trends and customer sentiment.
Develop a recommendation system for strategic product promotions.
Dataset
Subset of Amazon electronics reviews (120K entries) with key fields:

product_id, price, star_rating, review_body, review_date, category
Additional features: rating, user_id, helpful_vote, verified_purchase, etc.
Data Modeling
Conceptual Model:

One-to-Many: Users → Reviews, Products → Reviews
Many-to-Many: Products ↔ Categories, Stores, Images, Videos
Logical Model (MySQL Implementation):

Tables: Products, Categories, Users, Reviews, Stores
Associative Tables: ProductCategories, ProductStores, BoughtTogether
Methodology & Tools
ETL Pipeline: Python, AWS Glue
Storage & DB: Amazon S3, MySQL
Analysis: Pandas, NumPy, SQL
Visualization: Matplotlib, Tableau
Sentiment Analysis: NLTK, TextBlob
Recommendations: Scikit-learn, Surprise
Insights & Recommendations
High-performing categories: "All Electronics," "Computers," and "Camera & Photo" should be prioritized for Black Friday deals.
Sentiment trends: Positive sentiment dominates, but categories like "Software" show lower satisfaction.
COVID-19 impact: Increased demand for home office electronics can inform future promotions.
Strategy: Focus advertising on work-related electronics and high-rated products to maximize sales.


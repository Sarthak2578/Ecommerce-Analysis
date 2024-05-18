# Ecommerce-Analysis

E-commerce generates vast amounts of data, which provides opportunities to understand customer behavior, optimize marketing strategies, improve operational efficiency, and more. This project utilizes data from the Brazilian e-commerce platform "Olist," which includes information on 100,000 orders from 2016 to 2018 made across multiple marketplaces in Brazil. The dataset offers a multifaceted view of each order, including order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

## ProblemStatement
The primary objectives of this project are:
1. To explore and analyze the dataset to create a master dataset.
2. To research synthetic data generation methods based on the models developed from the analysis.

## Dataset
The dataset, provided by Olist, is composed of several CSV files, each representing different aspects of the e-commerce transactions. The files include:

- olist_orders_dataset.csv: Contains order-level information.
- olist_order_items_dataset.csv: Contains details about the items in each order.
- olist_customers_dataset.csv: Contains customer demographics and location data.
- olist_products_dataset.csv: Contains product details.
- olist_order_reviews_dataset.csv: Contains customer reviews and ratings.
- olist_order_payments_dataset.csv: Contains payment information for each order.
- olist_sellers_dataset.csv: Contains information about sellers on the platform.
- olist_geolocation_dataset.csv: Contains geographical coordinates of customer locations.

## Master Dataset Creation
The master dataset (master_df) was created by merging and cleaning the various datasets to provide a comprehensive view of each order. The process included:

- Loading all the CSV files.
- Merging datasets on common keys (e.g., order_id, customer_id).
- Handling missing values and duplicates.
- Feature engineering to create new attributes that can enhance analysis.
- Ensuring data types are appropriate for analysis and modeling.

## Dataset Link
You can download the dataset from the Olist Kaggle page (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Contributions
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

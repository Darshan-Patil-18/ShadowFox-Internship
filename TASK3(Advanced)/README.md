# Amazon Product Ratings and Reviews Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on an Amazon product dataset containing information about product prices, discounts, ratings, and customer reviews. The purpose of this analysis is to explore patterns in the dataset and understand how different factors such as discounts, ratings, and product categories relate to each other.

The analysis was performed using Python in a Jupyter Notebook environment using basic data analysis and visualization libraries.

## Dataset Description

The dataset contains information about more than 1000 Amazon products along with their ratings and reviews. The main attributes included in the dataset are:

* **product_id** – Unique identifier for each product
* **product_name** – Name of the product
* **category** – Product category
* **discounted_price** – Price after discount
* **actual_price** – Original price before discount
* **discount_percentage** – Discount percentage offered
* **rating** – Average rating of the product
* **rating_count** – Number of users who rated the product
* **about_product** – Description of the product
* **user_id** – ID of the user who wrote the review
* **user_name** – Name of the reviewer
* **review_id** – Unique review identifier
* **review_title** – Title of the review
* **review_content** – Content of the review
* **img_link** – Product image link
* **product_link** – Amazon product link

## Objectives

The main objectives of this analysis are:

* Explore the structure and characteristics of the dataset
* Identify patterns in product ratings
* Analyze the relationship between discounts and ratings
* Identify the most popular products based on review counts
* Visualize the distribution of product categories and ratings

## Tools and Libraries Used

The analysis was performed using the following tools and Python libraries:

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Jupyter Notebook / VS Code**

## Data Cleaning

Before performing analysis, the dataset was cleaned to ensure accuracy:

* Checked for missing values using `isnull().sum()`
* Removed rows with missing values in the `rating_count` column
* Converted price columns from string format to numeric values by removing symbols like ₹ and commas
* Checked for duplicate rows and removed them if present

## Exploratory Data Analysis

Several exploratory data analysis steps were performed to better understand the dataset:

* Examined dataset structure and summary statistics
* Analyzed distribution of product ratings
* Identified the most reviewed products
* Compared discount percentages with product ratings
* Visualized category distribution using bar charts

## Key Insights

Some key insights observed from the analysis include:

* Most product ratings are concentrated between **3.5 and 4.5**, indicating generally positive reviews.
* Products with higher discounts do not always receive higher ratings.
* A small number of products receive a very large number of reviews, showing higher popularity.
* Certain categories contain a larger number of products compared to others.

## Conclusion

This analysis demonstrates how exploratory data analysis techniques can be used to understand product ratings and customer feedback on an e-commerce platform like Amazon. By analyzing price, discount, and rating patterns, we can gain useful insights about product popularity and customer behavior.

## Author

Darshan Patil

# Apple Products Analysis

## About the Project

This project performs Exploratory Data Analysis (EDA) on an Apple Products dataset using Python.

The analysis focuses on product pricing, discounts, customer ratings, reviews, and RAM configurations to identify patterns and generate business insights.

The objective of this project is to practice data cleaning, data analysis, data visualization, and extracting meaningful insights from real-world data.

---

## Dataset Information

The dataset contains information about Apple products, including:

* Product Name
* Sale Price
* MRP (Maximum Retail Price)
* Discount Percentage
* Number of Ratings
* Number of Reviews
* Star Rating
* RAM
* Brand

---

## Project Objectives

* Understand the pricing structure of Apple products.
* Analyze discounts offered across products.
* Explore customer ratings and reviews.
* Study the relationship between RAM and pricing.
* Identify popular products based on customer engagement.
* Generate actionable business insights through data analysis.

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Analysis Process

### 1. Data Loading

* Imported dataset using Pandas.
* Examined dataset structure and dimensions.

### 2. Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Converted RAM values into numerical format for analysis.

### 3. Exploratory Data Analysis (EDA)

* Examined product pricing distribution.
* Identified top-rated products.
* Analyzed products with the highest ratings and reviews.
* Studied discount patterns.
* Compared RAM configurations with pricing.

### 4. Data Visualization

Created various visualizations including:

* Price Distribution Histogram
* Top Rated Products
* Most Reviewed Products
* RAM vs Average Sale Price
* Discount Distribution
* Correlation Heatmap
* Scatter Plots for Price vs Ratings and Reviews

---

## Key Insights

1. Apple products in the dataset are concentrated in the premium price range, reflecting the brand's premium market positioning.

2. Sale Price and MRP exhibit a very strong positive correlation, indicating that discounted prices closely follow the original pricing structure.

3. Products with larger discounts do not consistently achieve higher star ratings, suggesting that discounts alone are not a strong predictor of customer satisfaction.

4. A small number of products account for a large share of ratings and reviews, indicating that customer engagement is concentrated among a few popular products.

5. Products with more ratings generally receive more reviews, showing a strong relationship between product popularity and customer feedback.

6. Products with larger RAM configurations tend to have higher average selling prices, demonstrating the impact of hardware specifications on pricing.

7. Most products maintain star ratings above 4.0, indicating generally positive customer experiences.

8. Several high-priced Apple products continue to attract substantial numbers of ratings and reviews, indicating strong customer interest despite premium pricing.

9. Discount percentages vary significantly across products, suggesting selective promotional strategies rather than uniform discounting.

10. Many of the most-rated products also maintain strong star ratings, indicating a positive relationship between popularity and customer satisfaction.

11. RAM and Sale Price show a positive correlation, suggesting that storage capacity contributes to pricing, although additional factors also influence product cost.

---

## Project Structure

Apple-Products-Data-Analysis/

├── apple_data_analysis.ipynb

├── apple_products.csv

├── README.md

├── requirements.txt

└── screenshots/

```
├── correlation_heatmap.png

├── price_distribution.png

└── top_rated_products.png
```

---

## How to Run the Project

1. Clone the repository.
2. Install the required libraries.
3. Open the project in VS Code.
4. Open `Apple_Data_Analysis.ipynb`.
5. Run the notebook cells sequentially.

### Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## Conclusion

This project demonstrates the use of Python for data cleaning, exploratory data analysis, and visualization. Through this analysis, valuable insights were extracted regarding Apple product pricing, customer engagement, discounts, and product specifications.

The project helped strengthen practical skills in:

* Data Cleaning
* Data Visualization
* Exploratory Data Analysis (EDA)
* Business Insight Generation
* Python for Data Analytics

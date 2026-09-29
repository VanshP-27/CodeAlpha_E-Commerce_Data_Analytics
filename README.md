# E-Commerce Data Analytics & Web Scraping Project

## Project Overview
This project is part of the 1-month Data Analytics Internship at **CodeAlpha**. It focuses on web scraping product data from an e-commerce platform (`books.toscrape.com`), performing Exploratory Data Analysis (EDA), and generating publication-ready visual charts.

## Key Features & Workflow
1. **Task 1: Web Scraping (`Requests` & `BeautifulSoup`)**
   - Scraped 500 product records across 25 pages.
   - Extracted `Product_Title`, `Price_GBP`, `Star_Rating`, and `Stock_Status`.
   - Cleaned messy price strings into numerical formats and converted word ratings into standard integers.

2. **Task 2: Exploratory Data Analysis (`Pandas` & `NumPy`)**
   - Verified data integrity (0 missing values, correct data types).
   - Calculated descriptive statistics (mean, median, min, and max pricing).
   - Evaluated product rating distributions and average price per rating tier.

3. **Task 3: Data Visualization (`Matplotlib` & `Seaborn`)**
   - **Histogram & KDE:** Evaluated the overall price distribution of books.
   - **Bar Chart:** Visualized product volume across each star rating.
   - **Box Plot:** Analyzed price spread and variability across star categories.

## Project Structure
- `CodeAlpha_Data_Analytics_Project.ipynb` : Main Jupyter Notebook containing complete code for Scraping, EDA, and Visualization.
- `scraped_ecommerce_products.csv` : Cleaned dataset containing 500 scraped records.
- `ecommerce_eda_visualizations.png` : High-resolution exported EDA charts.

## Visual Insights
![EDA Visualizations](ecommerce_eda_visualizations.png)

## Tools & Libraries Used
- Python 3
- BeautifulSoup4 & Requests
- Pandas & NumPy
- Matplotlib & Seaborn
-

# Zomato Data Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on the Zomato Restaurant dataset using Python. The objective is to analyze restaurant types, customer ratings, online ordering preferences, votes, and pricing patterns to uncover meaningful business insights that can help restaurants improve customer experience and operational strategies.

---

## Objective

The primary objectives of this analysis are to:

- Understand the distribution of restaurant categories.
- Analyze customer ratings and voting patterns.
- Compare online and offline ordering behavior.
- Explore the relationship between restaurant type and online ordering.
- Visualize key trends using statistical charts.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset Information

The dataset contains restaurant-related information such as:

- Restaurant Type
- Customer Ratings
- Number of Votes
- Approximate Cost for Two People
- Online Order Availability

---

## Data Preprocessing

The following preprocessing steps were performed before analysis:

- Imported the dataset using Pandas.
- Converted rating values into numeric format.
- Checked dataset structure using `info()`.
- Verified data quality and null values.
- Prepared data for visualization and analysis.

---

## Exploratory Data Analysis

### 1. Restaurant Type Distribution

A count plot was created to analyze the distribution of restaurant categories.

**Insight**

- The majority of restaurants belong to the **Dining** category.

---

### 2. Votes by Restaurant Type

Restaurant types were grouped based on the total number of customer votes.

**Insight**

- Dining restaurants receive the highest number of customer votes, indicating greater customer engagement.

---

### 3. Rating Distribution

A histogram was used to visualize the distribution of restaurant ratings.

**Insight**

- Most restaurants have ratings concentrated within a moderate to high range, indicating generally positive customer experiences.

---

### 4. Cost Distribution

The approximate cost for two people was analyzed to understand restaurant pricing trends.

**Insight**

- Most restaurants fall within an affordable pricing range, making them accessible to a broad customer base.

---

### 5. Online vs Offline Ratings

A box plot was created to compare customer ratings for restaurants that offer online ordering versus those that do not.

**Insight**

- Restaurants offering **online ordering generally receive higher customer ratings**.
- Offline-only restaurants tend to have comparatively lower ratings.

---

### 6. Restaurant Type vs Online Ordering

A heatmap was used to examine the relationship between restaurant type and online ordering availability.

**Insight**

- Dining restaurants primarily receive offline orders.
- Cafés receive a larger proportion of online orders.
- Customers generally prefer dining in at restaurants while choosing online ordering for cafés.

---

## Visualizations Used

- Count Plot
- Line Plot
- Histogram
- Box Plot
- Heatmap

---

## Key Insights

- Dining is the most common restaurant category.
- Dining restaurants attract the highest number of customer votes.
- Most restaurants maintain moderate to high customer ratings.
- Online ordering is associated with better customer ratings.
- Cafés receive more online orders, whereas dining restaurants primarily serve offline customers.
- Pricing across restaurants remains affordable for most customers.

---

## Business Recommendations

- Restaurants should strengthen their online ordering services to improve customer satisfaction.
- Dining restaurants can enhance digital ordering platforms to capture additional online demand.
- Restaurant owners should regularly monitor customer ratings and feedback to improve service quality.
- Marketing strategies can be customized based on restaurant type and customer ordering preferences.

---

## Conclusion

This project demonstrates the use of Exploratory Data Analysis (EDA) techniques to uncover valuable insights from the Zomato dataset. By analyzing restaurant categories, ratings, customer preferences, and ordering behavior, the study provides actionable insights that can support better business decisions in the restaurant industry.

---

## Author

**Shubham Singh**

**Aspiring Data Analyst**

### Technical Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization

# 🍽️ Zomato Restaurant Analysis Dashboard

## 📌 Project Overview

The Zomato Restaurant Analysis Dashboard is a data analytics project developed using Python and Power BI. The project focuses on cleaning, analyzing, and visualizing restaurant data to uncover valuable insights related to customer preferences, restaurant performance, ratings, cuisines, pricing, online ordering, and table booking services.

The final outcome is an interactive Power BI dashboard that enables users to explore restaurant trends and make data-driven decisions.

---

# 🎯 Problem Statement

The restaurant industry generates large amounts of data related to customer ratings, votes, restaurant types, cuisines, pricing, online ordering, and table booking services. However, extracting meaningful insights from this raw data can be challenging.

The objective of this project is to analyze the Zomato restaurant dataset and build an interactive dashboard that helps identify:

- Popular restaurant locations
- Customer rating patterns
- Most common restaurant types
- Popular cuisines
- Online ordering trends
- Table booking availability
- Relationship between restaurant cost, ratings, and votes

By transforming raw restaurant data into actionable insights, businesses can better understand customer preferences and market trends.

---

# 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Power BI
- CSV Dataset

---

# 📂 Dataset Information

The dataset contains restaurant information such as:

- Restaurant Name
- Location
- Rating
- Votes
- Restaurant Type
- Cuisine
- Online Order Availability
- Table Booking Availability
- Approximate Cost for Two People
- Customer Reviews

---

# 🧹 Data Cleaning Process

The dataset contained missing values and inconsistent data formats.

### Steps Performed

### 1. Missing Value Analysis

```python
df.isnull().sum()
```

### 2. Handling Missing Values

Categorical columns were filled using Mode:

- location
- rest_type
- cuisines

Numerical columns were filled using Median:

- rate
- approx_cost(for two people)

### 3. Cleaning Approximate Cost Column

Removed commas and converted values into numeric format.

Example:

```text
1,500 → 1500
```

### 4. Cleaning Rating Column

Removed "/5" and converted values into numeric format.

Example:

```text
4.1/5 → 4.1
```

### 5. Data Type Conversion

Used:

```python
pd.to_numeric(errors='coerce')
```

to convert columns into proper numerical format.

### 6. Final Validation

Verified that all missing values were removed successfully.

---

# 📊 Exploratory Data Analysis (EDA)

Several visualizations were created using Python and Power BI to understand the data.

Analysis performed:

- Restaurant distribution by location
- Restaurant types analysis
- Cuisine analysis
- Rating distribution
- Online order analysis
- Table booking analysis
- Cost analysis
- Votes analysis

---

# 📈 Power BI Dashboard

The dashboard contains interactive visualizations and filters.

## KPI Cards

- Total Restaurants
- Average Rating
- Total Votes

## Slicers

- Location
- Online Order
- Book Table

## Visualizations

### Bar Charts

- Top Restaurant Locations
- Restaurant Types
- Rating Analysis

### Pie Charts

- Online Order Availability
- Table Booking Availability

### Treemaps

- Restaurant Type Distribution
- Cuisine Distribution

### Scatter Plot

- Cost vs Votes by Rating

---

# 🔍 Key Insights

## Location Analysis

- BTM contains the highest number of restaurants.
- HSR Layout and Koramangala also have significant restaurant presence.

## Restaurant Types

- Quick Bites is the most common restaurant type.
- Casual Dining is another major category.

## Online Ordering

- A large percentage of restaurants provide online ordering services.

## Table Booking

- Most restaurants do not offer table booking facilities.

## Ratings

- Most restaurants have ratings between 3.5 and 4.0.

## Cuisines

- North Indian cuisine is highly popular.
- Chinese and Italian cuisines are also widely available.

## Customer Engagement

- Restaurants with higher ratings generally receive more votes.
- Popular restaurants tend to attract greater customer interaction.

---

# 💼 Business Impact

This dashboard can help:

### Restaurant Owners

- Understand customer preferences
- Identify popular cuisines
- Analyze market competition

### Customers

- Explore restaurant options
- Compare ratings and services

### Investors

- Identify high-demand locations
- Evaluate restaurant market opportunities

---

# 🚀 Project Workflow

```text
Raw Dataset
      ↓
Data Cleaning using Python
      ↓
Handling Missing Values
      ↓
Data Transformation
      ↓
Exploratory Data Analysis
      ↓
Export Cleaned Dataset
      ↓
Power BI Dashboard Creation
      ↓
Business Insights
```

---

# 📷 Dashboard Features

✅ Interactive Dashboard

✅ KPI Cards

✅ Slicers

✅ Bar Charts

✅ Pie Charts

✅ Treemaps

✅ Scatter Plot

✅ Dynamic Filtering

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Missing Value Treatment
- Data Visualization
- Exploratory Data Analysis (EDA)
- Power BI Dashboard Development
- Business Intelligence
- Data Storytelling

---

# 🔮 Future Enhancements

- Sentiment Analysis on Customer Reviews
- Predictive Rating Analysis
- Restaurant Recommendation System
- SQL Integration
- Real-time Dashboard Updates

---

# 👩‍💻 Author

Pavani Sunkara
B.Tech Graduate | Aspiring Data Scientist & Data Analyst

Skills:
- Python
- SQL
- Power BI
- Pandas
- Data Visualization
- Machine Learning (Learning)

---

# ⭐ Conclusion

This project successfully transformed raw restaurant data into an interactive business intelligence dashboard. Through data cleaning, analysis, and visualization, meaningful insights were generated regarding restaurant trends, customer preferences, and market opportunities.

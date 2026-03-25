# Google Play Store Market Analysis

## Project Overview

This project explores the Google Play Store dataset to analyze app market structure, pricing behavior, rating patterns, and user sentiment.

The objective is to understand how applications are distributed across categories, how pricing relates to ratings, and how user reviews reflect overall sentiment toward free and paid applications.

---

## Dataset

The analysis is based on two datasets:

- `apps.csv`
- `user_reviews.csv`

The main dataset contains:

- 9,659 cleaned applications
- 33 categories
- Information about installs, price, rating, size, and type (Free/Paid)

---

## Methodology

### 1. Data Cleaning

- Removal of duplicate records
- Cleaning special characters from:
  - `Installs`
  - `Price`
- Conversion of numeric columns to float
- Validation of missing values

---

### 2. Exploratory Data Analysis

- Distribution of applications by category
- Rating distribution analysis
- Average rating calculation
- Category-level aggregation
- Size vs Rating relationship
- Price vs Rating analysis for paid applications

---

### 3. Free vs Paid Analysis

Comparison between Free and Paid apps including:

- Average rating
- Average size
- Average number of reviews
- Average installs
- Average price

---

### 4. Sentiment Analysis

User review data was merged with the apps dataset to analyze sentiment polarity.

- Removal of null sentiment values
- Sentiment polarity comparison between Free and Paid apps
- Visualization of sentiment distribution

---

## Key Observations

- Most apps are free
- Ratings are generally concentrated above 4.0
- Paid apps show slightly higher average rating
- A small number of apps have extremely high pricing
- Sentiment polarity shows variation between app types

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

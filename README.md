# Google Play Store App EDA

This repository contains an in-depth Exploratory Data Analysis (EDA) of the Google Play Store apps dataset, integrating user reviews and app metadata to uncover actionable business insights. The primary objective is to identify key factors that drive app success on the Play Store platform.

## Table of Contents

- [Overview](#overview)
- [Datasets](#datasets)
- [Problem Statement](#problem-statement)
- [Business Objective](#business-objective)
- [Data Preprocessing](#data-preprocessing)
- [Data Analysis](#data-analysis)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Author](#author)

## Overview

This project performs data cleaning, wrangling, merging, and visualization on two related datasets to understand trends, user behavior, and app characteristics that influence installs, ratings, revenue, and sentiment.

## Datasets

1. **Main App Dataset**  
   Contains features like: `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Type`, `Price`, `Content Rating`, `Genres`, `Last Updated`, `Current Ver`, `Android Ver`.

2. **User Reviews Dataset**  
   Contains features like: `App`, `Translated_Review`, `Sentiment`, `Sentiment_Polarity`, `Sentiment_Subjectivity`.

## Problem Statement

The Play Store is a competitive environment with millions of apps. Understanding which characteristics lead to better user reception, higher installs, and increased revenue can help developers make data-driven decisions.

## Business Objective

To help app developers, publishers, and marketers:
- Identify high-performing app categories and traits.
- Understand user sentiment and feedback patterns.
- Strategize pricing, content rating, and update frequency to boost engagement and profitability.

## Data Preprocessing

- Handled missing values and inconsistent data types.
- Removed duplicate records to ensure integrity.
- Parsed and standardized datetime and version-related fields.
- Merged both datasets on the `App` column.
- Created new metrics such as `Total Revenue = Price * Installs`.

## Data Analysis

A total of 21 visualizations were created to analyze:
- Rating distribution and correlation with price, size, and installs.
- Content and category distributions.
- Revenue patterns among paid apps.
- Sentiment distribution from user reviews.
- Trends over time and update relevance.

## Key Insights

- Over 92% of apps are free. Monetization via ads/in-app purchases is essential.
- Paid apps with unique value can still generate substantial revenue.
- Categories like FAMILY and GAME dominate in both volume and installs.
- High ratings are associated with smaller apps, frequent updates, and positive reviews.
- User sentiment aligns closely with app ratings and can guide feature development.
- Apps with high installs tend to receive more reviews, indicating strong user engagement.
- Regular updates correlate with higher average ratings.

## Conclusion

This analysis provides a roadmap for building successful Play Store apps. Developers should focus on optimizing app size, maintaining regular updates, monitoring sentiment feedback, and selecting the right category based on demand. While free apps dominate, niche paid apps can perform exceptionally well when they deliver clear value.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Author

**Muskaan Gaur**

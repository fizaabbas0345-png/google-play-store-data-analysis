# google-play-store-data-analysis
Data cleaning, exploratory data analysis, and visualization of the Google Play Store dataset using Python and Pandas.
# Google Play Store Data Analysis

## Overview

This project explores and analyzes the Google Play Store dataset using Python and Pandas. The objective was to clean the raw data, perform exploratory data analysis (EDA), and identify trends related to app categories, ratings, installs, reviews, pricing, and update activity.

## Dataset Information

The dataset contains information about applications available on the Google Play Store, including:

* App Name
* Category
* Rating
* Reviews
* Size
* Installs
* Type (Free/Paid)
* Price
* Content Rating
* Genres
* Last Updated
* Android Version

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Data Cleaning Process

The following data cleaning steps were performed:

* Removed corrupted records
* Handled missing values
* Filled missing ratings using statistical methods
* Filled missing values in categorical columns using mode
* Converted Reviews column to numeric format
* Converted Installs column to numeric format
* Cleaned and converted Price column
* Converted Last Updated to datetime format
* Checked data consistency and validity
* Removed duplicate records

## Exploratory Data Analysis

The analysis focused on:

* Distribution of app ratings
* Category-wise app counts
* Category-wise installs
* Free vs Paid applications
* Most reviewed applications
* Most installed applications
* Highest-rated categories
* Update trends over time

## Visualizations

The project includes visualizations for:

* Rating Distribution
* Top App Categories
* Free vs Paid Apps
* Category-wise Installs
* Reviews vs Installs Relationship

## Key Insights

* Free apps dominate the Google Play Store.
* A small number of categories account for the majority of app installs.
* Reviews and installs show a strong positive relationship.
* Most apps maintain ratings above 4.0.
* App update activity increased significantly in recent years.

## Project Structure

```text
Google_Play_Store_Analysis.ipynb
README.md
```

## How to Run

1. Clone the repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Run all cells sequentially.
4. Explore the analysis and visualizations.

## Author

FIZA ABBAS ALI

## Aspiring Data Analyst | Python | Pandas | Data Visualization

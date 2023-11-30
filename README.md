# Boston Airbnb Listings Analysis
This repository contains a Python script for analyzing the Boston Airbnb listings dataset. The script focuses on two main aspects:
1. Answering specific questions about the characteristics of Airbnb listings in different neighborhoods.
2. Identifying features that most significantly influence the listing prices.

# Description
The analysis is divided into two parts:
Part 1: Determines neighborhoods with specific characteristics based on the amenities provided, the cleanliness of the neighborhood, and the highest review scores.
Part 2: Implements a regression analysis to identify which features have the most significant impact on the price of an Airbnb listing.

# Requirements
-  Python 3.8 and above
- Pandas
- Scikit-learn

# Dataset
The dataset used is the listings.csv file which is available publicly at: https://www.kaggle.com/datasets/airbnb/boston , contains detailed listings data for Airbnb in Boston. The dataset includes various features such as neighborhood, room type, amenities, number of reviews, and price.

# Usage
1. Clone this repository to your local machine.

2. Place the listings.csv file in the same directory as the script.

3. Run the script using Python.

**The script will output:**
1. The neighborhood with the most Airbnb houses with WIFI and laptop-friendly workplaces.
2. The neighborhood with the most Airbnb houses with cleansed neighborhoods.
3. The neighborhood with the largest number of highest review scores.
4. A regression analysis result showing the features influencing the price the most.

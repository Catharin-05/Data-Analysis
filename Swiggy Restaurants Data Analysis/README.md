# Data Analysis Projects
This repository includes analysis on various datasets such as restaurant ratings, customer churn, and more. Each notebook provides insights and visualizations based on the dataset.


## Table of Contents
- [Swiggy Restaurants Data Analysis](#SwiggyRestaurantsDataAnalysis)
- [Liscence](#liscence)
- [Contact](#contact)

## Projects
## Project 1: Swiggy Restaurants Data Analysis

**Overview:**
The objective of this analysis is to provide actionable insights and recommendations for stakeholders in the Indian restaurant industry by thoroughly examining various factors influencing customer preferences, service offerings, costs, and regional performance. The analysis aims to:

* Identify Popular Food Categories: Determine the most popular food categories and understand regional preferences for vegetarian and non-vegetarian options.

* Analyze Rating Distributions: Explore the distribution of restaurant ratings and identify how they vary with cost, location, and additional services.

* Evaluate Cost Impacts: Understand the relationship between dining costs and customer ratings, and assess if higher costs correlate with better ratings.

* Examine Regional Performance: Identify which cities and areas have the highest and lowest restaurant ratings, and how dining costs vary across regions.

By achieving these objectives, the analysis will deliver valuable insights that can help restaurant owners and stakeholders optimize their strategies, improve service offerings, and make data-driven decisions to enhance their market position and customer experience.

**Key Findings:**
- North Indian, Fast Food, Indian Chinese, South Indian, and Snacks emerge as the most prevalent food categories among restaurants, reflecting diverse culinary preferences across different regions of India.
- Restaurants where the cost for two people falls between 50 and 90 typically offer higher cost efficiency, indicating that this price range generally provides better value for money or greater satisfaction.
- Approximately 36.25% of restaurants have ratings higher than the average rating of other restaurants in their respective areas. This suggests that a notable proportion, though less than half, of restaurants perform better compared to their local competitors.
- Mumbai emerges as the most expensive city for dining out, with an average cost of Rs. 450, followed by Kolkata and Bangalore. Other cities typically have average costs ranging between Rs. 200 and Rs. 300, highlighting regional variations in dining expenditure.

**Implementation Details:**
1. Data Collection & Preparation:
-  Understanding the trends and patterns in the restaurant industry is crucial for establishing new restaurant or even for increasing the profits for already existing restaurants.
- The dataset is taken from Kaggle. The dataset contains information about restaurants in the top 49 most populous cities in India.
2. Methodology:
The methodology followed in this project are as follows:
- At first, a basic data exploration is done to understand the data, find null values, outliers and  to get the statistical summary of the data.
- The data is cleaned and null values are dealt with appropriate methods.
- Extra features are built to derive more insights from the data.
- Various visualizations are plotted to indentify patterns and trends from the dataset.
- The insights and findings are presented as a summary
3. Challenges & Solutions:
- Challenge: The Rating column of the dataset, an important feature for the analysis have approximately 55% of the data missing. This posed a significant challenge because ignoring such a large portion of data would have led to incomplete and potentially biased insights. Moreover, the Rating is key to understanding customer satisfaction and making recommendations.
- Solution: For each missing rating, the average rating of the same food category within the same locality was calculated and used as the imputed value. This method ensured that the imputed values were contextually relevant and maintained the integrity of the data.

**Usage:**
1. Clone the repository: `git clone https://github.com/Catharin-05/Data-Analysis.git`
2. Navigate to the project folder: `cd Swiggy Restaurants Data Analysis.ipynb`
3. Run the analysis: `Swiggy Restaurants Data Analysis.ipynb`

The following are dependencies required for setting up this project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- gdown
- os
- missingno
- wordcloud





## Liscence
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions, please reach out to nivithacatharin@gmail.com

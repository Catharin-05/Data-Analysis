# Airlines Customer Satisfaction Analysis
This repository contains a comprehensive analysis of customer satisfaction data for Invistico Airlines. The goal of this analysis is to derive actionable insights and recommendations to enhance the airline's service offerings and improve customer satisfaction levels.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Findings](#key-findings)
- [Implementation Details](#implementation-details)
- [Challenges & Solutions](#challenges--solutions)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Project Overview
The objective of this analysis is to predict customer satisfaction based on various factors such as demographics, travel details, and service ratings. The dataset consists of feedback from customers who have flown with Invistico Airlines, covering a range of services and customer experiences. By analyzing this data, we aim to:
* Identify key factors influencing customer satisfaction.
* Understand the distribution of customer ratings across different demographics and services.
* Provide actionable recommendations for service improvement to enhance customer experiences.

## Key Findings
- **Customer Satisfaction Rates**: Overall, 54.7% of customers reported satisfaction, while 45.3% were dissatisfied.
- **Gender Distribution**: Female customers showed a higher dissatisfaction rate (24,000) compared to male customers (35,000).
- **Loyalty Impact**: Loyal customers are significantly more satisfied (65,000 satisfied) compared to disloyal customers (5,000 satisfied).
- **Type of Travel**: Business travelers had a higher satisfaction rate (52,000 satisfied) compared to personal travelers (19,000 satisfied).
- **Service Ratings**: The seat comfort ratings were notably high, with many customers giving a rating of 5 (around 4,700).
- **Flight Distance**: Most customers traveled distances up to 2,000 miles, with outliers for longer distances causing delays.
- **Age Distribution**: Younger customers (10-25) are traveling more frequently for medium-haul flights, while older customers tend to avoid longer distances.

## Implementation Details
1. **Data Collection & Preparation**:
   - The dataset was sourced from Kaggle, containing customer feedback and flight data for Invistico Airlines.
   - Initial data exploration was conducted to identify null values, outliers, and the overall statistical summary.

2. **Methodology**:
   - Basic data exploration to understand data characteristics and statistical distribution.
   - Data cleaning processes to handle missing values and outliers.
   - Feature engineering to derive additional insights, such as total delay and customer loyalty metrics.
   - Bivariate analysis to explore relationships between customer demographics and satisfaction levels.

3. **Challenges & Solutions**:
   - **Challenge**: Missing values in key features, such as satisfaction ratings, posed a risk of incomplete insights.
   - **Solution**: Imputation strategies were applied to fill missing values based on contextual relationships in the data, ensuring relevance and accuracy.

## Usage
1. Clone the repository: `git clone https://github.com/Catharin-05/Data-Analysis.git`
2. Navigate to the project folder: `cd Airlines Customer Satisfaction`
3. Run the analysis: Open `Airlines_Customer_Satisfaction_Analysis.ipynb` in Jupyter Notebook or any compatible environment.

### Dependencies
The following dependencies are required for setting up this project:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- gdown
- os
- missingno

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions or inquiries, please reach out to nivithacatharin@gmail.com.

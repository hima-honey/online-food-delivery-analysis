# online-food-delivery-analysis
Exploratory data analysis of online food delivery customers using Python, Pandas, and Matplotlib, with customer behavior insights and business recommendations.

# Online Food Delivery Customer Analysis

## Project Overview

This project analyzes customer behavior in an online food delivery dataset using Python.

The analysis focuses on customer demographics, ordering behavior, customer type, family size, education, income, occupation, location, and feedback.

The goal is to identify meaningful customer patterns that can support marketing, customer targeting, and retention strategies.

## Objectives

- Understand online food ordering behavior
- Analyze different customer segments
- Identify meaningful customer patterns
- Explore relationships between customer attributes and ordering behavior
- Generate business recommendations from the analysis

## Dataset

The dataset contains customer information related to online food delivery behavior.

### Main Features

- Age
- Gender
- Marital Status
- Occupation
- Monthly Income
- Educational Qualifications
- Family Size
- Customer Type
- Latitude
- Longitude
- Pin Code
- Output
- Feedback

## Data Cleaning

The following preprocessing steps were performed:

1. Checked for duplicate records
2. Removed duplicate rows
3. Checked for missing values
4. Identified and removed the redundant `Unnamed: 13` column
5. Created age groups for analysis

## Exploratory Data Analysis

The project investigates the following questions:

1. Does gender influence online food ordering?
2. Which occupations have the most online-ordering customers?
3. Which pincodes have the highest number of ordering customers?
4. Which age group orders online food the most?
5. How does family size relate to customer type?
6. Does educational qualification relate to online food ordering?
7. How does feedback vary by customer type?
8. Does monthly income relate to online food ordering?
9. Does gender relate to customer type?

## Key Insights

- Male customers have a slightly higher online-ordering rate than female customers.
- Customers aged 22–25 contribute the largest number of online orders.
- Certain occupations and pincodes contribute a larger number of online-ordering customers.
- Customer type shows an association with family size.
- Post Graduate customers have the highest ordering rate among the education groups.
- Regular and Frequent customers show slightly higher positive-feedback rates than New customers.
- The `No Income` category has the highest ordering rate in this dataset.
- Customer-type distributions are broadly similar across genders.

> These findings describe patterns in the dataset and should not be interpreted as causal relationships.

## Business Recommendations

Based on the analysis:

- Target high-ordering age groups with relevant promotions.
- Use location-based campaigns in areas with higher ordering activity.
- Create family-size offers for different household sizes.
- Focus retention strategies on Regular and Frequent customers.
- Monitor feedback from newer customers to improve customer experience.
- Use occupation and education patterns carefully for customer segmentation.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook



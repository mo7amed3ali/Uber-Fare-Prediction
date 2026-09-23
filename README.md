# Uber Fare Prediction

## Task 1 — Exploratory Data Analysis (EDA)

This project is part of an **ML Internship Program** and focuses on performing Exploratory Data Analysis on an Uber ride dataset before building machine learning models.

## Project Objective

The main objective of this task is to understand the dataset, identify important patterns and relationships, detect data quality issues, and extract insights that can guide the machine learning stage.

## Dataset

The dataset contains **500,000 ride records** with information about:

* Fare amount
* Passenger count
* Car condition
* Weather condition
* Traffic conditions
* Pickup and drop-off coordinates
* Trip distance
* Airport distances
* Date and time information

## Data Cleaning

Several data quality issues were investigated and handled, including:

* Missing values
* Negative and zero fare amounts
* Invalid passenger counts
* Invalid coordinate values
* Suspicious distance values
* Extremely high fares associated with very short distances

After cleaning, the dataset contained **487,742 records**.

## Exploratory Data Analysis

The analysis investigated the following questions:

1. Does passenger count affect fare amount?
2. Does car condition influence fare amount?
3. At what hour are average fares highest?
4. Does traffic condition affect trip fare?
5. Is trip distance strongly related to fare amount?
6. At what time are ride requests most frequent?
7. Does weather condition influence trip distance?
8. Are rides closer to airports more expensive?
9. How is fare amount distributed?
10. Which numerical features have the strongest relationship with fare amount?
11. At what hours and on which days are ride requests most frequent?

## Key Findings

* **Distance** showed the strongest positive linear relationship with fare amount, with a correlation of approximately **0.838**.
* Passenger count did not show a clear increasing relationship with fare amount.
* Fare distributions were very similar across different car conditions.
* Traffic condition showed relatively small differences in average and median fares.
* Average fares were highest around **5 AM**.
* Ride demand was highest during the evening, particularly around **7 PM**.
* Weather conditions showed very similar average trip distances.
* Distance to the nearest airport had almost no linear correlation with fare amount.
* Fare amounts were **right-skewed**, with most fares below **$20**.
* Ride demand varied across both hours and days of the week.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Files

```text
Uber-Fare-Prediction/
│
├── task_1.ipynb
├── Uber Fare Prediction.pdf
└── README.md
```

## Next Step

The cleaned dataset and EDA findings will be used as the foundation for the next stage of the project:

**Machine Learning Model Development and Fare Prediction**

## Author

**Mohamed Ali**

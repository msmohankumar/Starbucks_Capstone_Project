# Starbucks_Capstone_Project

# Seattle_Airbnb_Listings_Comprehensive-Analysis-of-Listings

[Starbucks Capstone Challenge_blog_post](https://medium.com/@msmohan.kumar2/6f93f9240199)





![Main_page](https://github.com/msmohankumar/Seattle_Airbnb_Listings_Comprehensive-Analysis-of-Listings/assets/153971484/04c030e3-3bdd-4cad-975f-77c3fcb02314)


## Overview

The above project investigates customer behavior on the Starbucks rewards mobile app, particularly focusing on their response to different types of offers. It aims to determine which demographic groups respond best to which offer types and to develop insights for targeted marketing strategies.

**Key aspects investigated include:**

* Offer Types: Analysis of the types of offers available (BOGO, discount, informational) and their distribution among customers.
* Demographics: Exploration of customer demographics such as age, gender, and income, and their distribution within the customer base.
* Offer Response: Examination of customer actions in response to offers, including offer received, viewed, and completed events.
* Machine Learning Model: Building a machine learning model to predict customer response to offers based on demographic and offer-related features.
* Overall, the project aims to provide insights into customer behavior and preferences regarding Starbucks offers, ultimately helping Starbucks optimize their marketing strategies and enhance customer engagement.


# Methods Used

## The project employs various methods to investigate customer behavior and build a predictive model. These methods include:

## Data Cleaning:
- ** Handling missing values.
- ** Renaming columns for clarity.
- ** Encoding categorical variables.
- ** Scaling numerical features.
## Exploratory Data Analysis (EDA):
- ** Visualization techniques such as bar plots and histograms to explore the distribution of demographic variables, offer types, and customer actions.
- ** Analysis of customer demographics, offer types, and actions taken on offers to identify patterns and trends.
## Machine Learning Modeling:
- ** Splitting the data into training and testing sets.
- ** Training and testing different classification algorithms (KNeighbors, RandomForest, DecisionTree) to predict customer response to offers.
- ** Using F1 score as the evaluation metric to assess the performance of the models.
## Visualization:
- ** Utilizing seaborn and matplotlib libraries for data visualization, including bar plots, pie charts, and count plots, to present insights from the data exploration phase.

## Overall, these methods help in understanding customer behavior, identifying influential factors, and building a predictive model to optimize marketing strategies

## Getting Started

**Prerequisites:**

* Anaconda and Jupyter Notebook (https://www.anaconda.com/)


**Project Structure:**

* Starbucks_Capstone_Project/
*
* ├── data/
* │  ├── portfolio        # Calendar data from Kaggle
* │  ├── profile        # Listings data from Kaggle
* │  └── transcript          # Reviews data from Kaggle
* ├── Jupyter note processed data  # Feature/amenity analysis
* ├── best_model_rf  # Best model pkl file
* ├── README.md              # Project documentation
* ├── LICENSE                # License information


**Run the Analysis:**

1. Clone this repository.
2. Open Jupyter Notebook and navigate to the project directory.
3. Open the Jupyter Notebook files :
    * Seattle_Airbnb_Listings_Comprehensive-Analysis-of-Listings.ipynb
    

## Technologies Used

* **Programming Language:** Python 3 (executed in Jupyter Notebook)
* **Data Manipulation:** Pandas
* **Machine Learning:** scikit-learn
* **Visualization:** Matplotlib


## Developers

* M S Mohan Kumar

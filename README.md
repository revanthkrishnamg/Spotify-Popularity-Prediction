# Spotify Popularity Prediction

## Overview
This project focuses on developing predictive models to estimate the popularity of songs on Spotify. These models aid stakeholders in the music industry, such as producers and marketers, by providing insights that can inform decisions related to artist signings, song selections, marketing strategies, and promotional activities.

## Outline

**Notebook - 1: (Part_A.ipynb)**
* I.    Importing the dataset
* II.   Data Cleaning 
* III.  Exploratory Data Analysis (EDA) 
* IV.   Popularity Prediction using Regression

**Notebook - 2: (Part_B.ipynb)**
* IV.   Popularity Prediction using Classification - Oversampling

**Notebook - 3: (Part_C.ipynb)**
* IV.   (Continued) Popularity Prediction using Classification - Undersampling
* V.    Result comparison between Regression vs Classification 
* VI.   Conclusion

## Predictive Modeling for Song Popularity

### Business Understanding
**Objective:** The primary goal is to develop a model to predict song popularity. This model will assist stakeholders in the music industry, such as producers and marketers, in making informed decisions regarding artist signings, song selections, marketing strategies, and promotional activities.

### Data Understanding
**Data Collection:** Acquired a comprehensive dataset from Spotify, featuring a wide array of tracks along with their features and popularity scores.

**Exploratory Data Analysis (EDA):** Conducted an in-depth analysis to examine the distributions of various features and the target popularity scores. Also investigated the relationships between different features and how they correlate with the popularity scores.

### Data Preparation
**Data Cleaning:** Addressed missing values and removed irrelevant columns to enhance the quality and relevance of the data.

**Feature Engineering:** Implemented cyclical and one-hot encoding for categorical features to improve model interpretability. Applied power transformations on continuous features to normalize distributions for the linear models, to ensure that the model's assumptions are met.

### Modelling
**Approach:** Explored both regression and classification models to determine the most suitable approach for predicting song popularity.

**Class Imbalance Solutions:** Utilized techniques such as SMOTE and undersampling for the class imbalance issue, ensuring that the model performs well across all classes.

**Model Selection and Optimization:** After identifying challenges with regression models, with how they were overfitting with low R² values, focused towards classification models. Used traditional machine learning models like Random Forest and XGBoost, and fine-tuned them using RandomizedSearchCV to achieve optimal performance.

### Evaluation
**Model Evaluation:** Evaluated the models' performance thoroughly to find the best model close to being a generalized model (having low bias and low variance).

**Feature Importance Analysis:** Conducted an analysis to find the features that significantly influence song popularity, informing future feature selection and engineering efforts.

### Deployment
**Strategic Recommendations:** Provided actionable insights and data-driven recommendations to stakeholders in the music industry, aiming to use the predictive model for strategic planning.

**Future Directions:** Emphasized the importance of exploring more sophisticated modeling techniques (deep learning) and integrating additional data sources to further enhance model insights and performance.

### Conclusion
This project, guided by the CRISP-DM methodology, underscores the transformative potential of predictive modeling in the music industry. It highlights the necessity for agility and continuous adaptation to new musical trends and consumer preferences, paving the way for more strategic and informed decision-making processes.

# Google Play Store App Rating Prediction Analysis(By using Python – Jupyter Notebook)
This project focuses on analyzing the Google Play Store dataset to gain meaningful insights about mobile applications. The dataset contains over 10,000 apps with various attributes such as name, category, rating, reviews, size, installs, price, type, content rating, and more.


## Dataset used
Dataset = "https://github.com/SubhankarMukherjee-portfolio/Google-Play-Store-Apps-Rating-Prediction/blob/main/googleplaystore.csv?plain=1"

## The goal of this project is to:
1) Clean and preprocess the raw data
2) Perform exploratory data analysis (EDA) to understand key distributions and trends
3) Use visualization techniques to uncover hidden patterns
4) Apply machine learning models to predict app ratings and classify apps based on various features

## Questions solved
1)	 What is the distribution of the number of apps across different categories?
2)	How are apps distributed across various genres?
3)	Which top genres have the highest total install counts?
4)	What is the distribution of apps by content rating?
5)	What are the most common words used in app names (Word Cloud)?
6)	How is the number of apps distributed across different rating values?
7)	What is the distribution of Free vs. Paid apps on the Play Store?
8)	How installs are distributed across different app categories?
9)	Which 15 categories have the most user reviews?
10)	Which individual apps have received the most user reviews?
11)	Which top 20 apps have the largest file sizes individually?
12)	Which categories have the highest average app size?
13)	Which top 20 apps are the most expensive?
14)	Which categories have the highest average app price?
15)	Is there any relationship between an app’s price and its rating?
16)	How does content rating (age group) affect app ratings?
17)	What is the relationship between the number of reviews and app ratings?
18)	Among apps rated 5 stars, how many are free vs. paid?
19)	Machine Learning Applied –
      Can we predict app ratings using regression models based on features like size, installs, reviews, and price?
      Can we classify apps (e.g., high-rated vs. medium rated vs. low-rated) using classification models based on available attributes?

## Libraries Used
The following Python libraries were used during the data cleaning, exploration, visualization, and analysis phases:
1) NumPy – for efficient numerical operations and handling arrays
2) Pandas – for data manipulation, cleaning, and analysis
3) Matplotlib – for basic data visualizations and plotting
4) Seaborn – for advanced, statistical, and beautiful visualizations
5) Scikit-learn (sklearn) – for machine learning algorithms, preprocessing, and model evaluation
6) XGBoost – for high-performance boosting algorithms used in classification and regression
7) scipy.stats – for statistical functions and hypothesis testing
8) statsmodels – for statistical modeling and regression analysis
9) Keras – for deep learning and building neural networks
10) WordCloud – to generate word clouds from app names or descriptions to show common terms

## Python file (Jupyter Notebook)
Python File = "https://github.com/SubhankarMukherjee-portfolio/Google-Play-Store-Apps-Rating-Prediction/blob/main/Google%20Playstore%20Apps%20rating%20Prediction%20_%20ML%20_%20FA%20_%20DA%20and%20SQL%20projects%20.ipynb"

## PowerPoint presentation
PPT = "https://github.com/SubhankarMukherjee-portfolio/Google-Play-Store-Apps-Rating-Prediction/blob/main/Google%20Playstore%20Apps%20rating%20Prediction.pptx"


## ML model results
1) Regression and classification models were applied to predict app ratings based on various features like size, installs, reviews, and price.
2) Regression model  -  The Gradient Boosting achieved the best results with the lowest RMSE (0.474) and the highest R² score (0.14), showing relatively better prediction accuracy. XGBoost followed closely with similar performance metrics. Random Forest and SVR showed moderate performance but had low R² values. Decision Tree and SGD performed poorly, especially Decision Tree with a negative R², indicating over fitting and weak predictive power overall. In overall regression models performed poorly overall, with low R² scores indicating weak predictive power.
3) Classification model  - Among all models, Random Forest achieved the highest accuracy of 75.81% and the best macro F1-score of 0.42, showing relatively balanced performance across classes. Gradient Boosting and XGBoost followed closely with macro F1-scores around 0.41, offering better recall for minority classes. SVC and SGD models performed poorly, failing to identify any minority class (1, 2, 3), as reflected in zero F1-scores for those classes. Overall, class imbalance significantly impacted model performance, and most models favored the majority class (class 0). In overall classification models showed good overall accuracy, with Random Forest and Gradient Boosting performing best in terms of precision and F1-score.


## Final Observations & Storyline
1) The Google Play Store showcases a dominant trend towards free apps, which make up around 93.1% of the total, leaving only 6.9% for paid apps. This indicates the accessibility of the platform, with most users able to enjoy apps without spending money. Additionally, the "Everyone" content rating is the most common, highlighting that a large portion of apps cater to users of all age groups, while Teen and Mature 17+ rated apps are less prevalent.
2) In terms of genres, Tools, Entertainment, and Education dominate the app landscape, signaling a balanced mix of utility and recreational apps. Communication apps take the lead in install counts, followed by Social and Productivity apps, reflecting the importance of staying connected and organized in today's digital world. Games stand out as the largest in average app size, while Finance and Lifestyle apps command higher prices, suggesting a shift towards premium experiences in niche categories.
3) Trends also show that free apps are the most prevalent among those with the highest ratings, with 89.7% of apps rated 5 stars being free. The relationship between reviews and ratings is evident, as higher-rated apps tend to gather more reviews, reinforcing the importance of user satisfaction in driving engagement. As the Google Play Store continues to evolve, free and feature-rich apps dominate, but paid apps, particularly in specific categories like Finance and Lifestyle, continue to offer premium experiences. 









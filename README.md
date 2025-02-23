Play Store Apps Data Analysis

Introduction

The Play Store hosts a diverse range of applications, and analyzing this data helps developers and businesses understand market trends, improve their apps, and increase user engagement.

In this project, we cleaned and preprocessed the Play Store dataset, addressed missing values, outliers, and other data issues to extract valuable insights.

Dataset Description

The dataset includes the following columns:

Application name: Name of the application

Category: Category of the app

Rating: User rating of the app

Reviews: Number of user reviews

Size: Size of the app

Installs: Number of installs

Type: Free or Paid

Price: Price of the app

Content Rating: Target age group

Genres: Genres the app belongs to

Current Ver: Current version of the app

Android Ver: Minimum Android version required

Data Cleaning Tasks

Fixed and standardized the "Rating," "Size," and "Price" columns

Handled missing values and outliers

Corrected categorical data in "Category" and "Android Ver"

Analytical Questions and Results

Most expensive app: Found the most expensive app on the Play Store

Genre with highest number of apps: Identified the genre with the most apps

Average size of free vs. paid apps: Compared the average size

Top 5 most expensive apps with perfect rating: Listed these apps

Apps with more than 50K reviews: Counted the number of apps

Average price by genre and installs: Calculated the average price and visualized it

Apps with rating > 4.7: Counted the number and calculated their average price

Google's estimated revenue from apps with 5M+ installs: Estimated based on a 30% cut from app sales

Maximum and minimum sizes of free vs. paid apps: Compared the sizes

Correlation analysis: Explored the relationship between rating, reviews, size, and price

Number of free/paid apps across content ratings: Visualized the distribution

Apps compatible with Android version 4.x: Counted the compatible apps

Visualizations

Bar charts, scatter plots, and histograms to visualize trends

Heatmaps to show correlations

How to Run the Project

Clone the repository

Install the required libraries using pip install -r requirements.txt

Open the Jupyter Notebook and follow the analysis step-by-step

Conclusion

This project provided valuable insights into Play Store apps, helping understand trends, app performance, and revenue potential.




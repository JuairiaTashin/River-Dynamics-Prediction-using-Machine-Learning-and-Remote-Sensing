# Riverbank Erosion and Accretion Prediction Using Machine Learning

## Project Overview

Riverbank erosion and accretion are major environmental concerns in Bangladesh. Every year, changing river boundaries affect nearby communities, agricultural land, and natural ecosystems. Understanding these changes is important for better river management and environmental planning.

This project explores the use of machine learning to analyze and predict riverbank erosion and accretion in five rivers of coastal Bangladesh: **Bishkhali, Baleshwar, Payra, Shibsa, and Pasur**. We use satellite imagery, remote sensing indices, and geographical information to study how riverbank areas change over time. The main goal is to identify patterns of erosion and accretion and explore how machine learning can support river monitoring and environmental research.

## Methodology

The project combines satellite image analysis, geospatial data processing, and machine learning techniques. Landsat and Sentinel-2 satellite imagery are used to observe changes in riverbank areas over different years. Google Earth Engine (GEE) is used for collecting and processing satellite data.

To understand changes in land and water conditions, we extract several remote sensing indices, including NDVI, NDWI, NDBI, SAVI, MSI, NBR, and BAI. We also consider land cover information such as water, vegetation, built-up areas, and bare land, along with geographical features like elevation, slope, and soil texture.

After collecting the data, we perform data cleaning, preprocessing, Exploratory Data Analysis (EDA), and feature engineering to prepare it for machine learning. Erosion and accretion are classified into three categories: Low, Medium, and High. We also explore class imbalance handling techniques such as SMOTE and ADASYN.

Finally, we experiment with different machine learning algorithms, including Logistic Regression, Random Forest, Gradient Boosting, AdaBoost, Support Vector Machine, Naive Bayes, K-Nearest Neighbors, Decision Tree, and XGBoost, to analyze and classify erosion and accretion patterns.

## Environmental Contribution

Riverbank erosion and accretion can have a lasting impact on both human lives and the natural environment. Through this project, we aim to better understand these changes using satellite data and machine learning.

By identifying areas vulnerable to erosion, this research could help improve awareness of riverbank changes and their possible effects on nearby settlements, agricultural land, and vegetation. The analysis may also provide useful insights for monitoring river boundaries and understanding changes in surrounding land cover.

We hope this work can contribute to future environmental research and support data-driven approaches to river monitoring, riverbank protection, and sustainable land management in Bangladesh.

## Future Work

There is still plenty of room to improve and expand this research. In the future, we would like to incorporate higher-resolution satellite imagery to make the analysis more detailed and explore advanced machine learning and deep learning models for better predictions.

We also aim to include river flow and hydrodynamic information to gain a better understanding of the natural processes behind erosion and accretion. Another important direction is improving the analysis of areas where erosion and accretion occur simultaneously. Further validation using field observations could also help assess how well the predictions reflect actual riverbank conditions.

In the long term, the study could be extended to more rivers and other vulnerable regions of Bangladesh.


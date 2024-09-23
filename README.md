# SCT_ML_2
 Task on k-means clustering for customer segmentation
     This project applies the K-means clustering algorithm to segment retail store customers based on purchase history. It involves data exploration, clustering, and visualization to identify distinct customer groups, enabling targeted marketing and business insights. Tools used include Python, pandas, Scikit-learn, and Seaborn.
## Project Overview

The goal of this project is to segment customers into clusters based on their age, annual income, and spending score. By clustering customers, businesses can better understand customer behavior and tailor their marketing strategies.

## Dataset

The Kaggle Dataset link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Dependencies
  To run this project, you need to insatll the following Python packages:
 - Pandas: For data manipulation and analysis
     bash
      pip install pandas 
 - scikit-learn: A library for machine learning algorithms and tools.

     bash
      pip install scikit-learn
 - matplotlib: A library for creating visualizations.

      bash
           pip install matplotlib
 - seaborn: A librray for statistical data visualization

    bash
      pip install seaborn

## Steps

1. *Data Loading and Exploration*:
    - Load the dataset using Pandas.
    - Check the shape, data types, and missing values of the dataset.
    - Generate descriptive statistics.

2. *Data Visualization*:
    - Plot histograms for age, annual income, and spending score distributions.

3. *Clustering*:
    - Select features for clustering.
    - Determine the optimal number of clusters using the elbow method.
    - Apply K-means clustering with the optimal number of clusters.
    - Add cluster labels to the dataset.

4. *Visualization of Clusters*:
    - Plot scatter plots to visualize clusters based on annual income vs spending score and age vs spending score.

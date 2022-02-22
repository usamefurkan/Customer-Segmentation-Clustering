# Customer-Segmentation-Clustering

## Overview
The project aims to segment there customer base in order to help targeted marketing and understanding their buying habits

- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment

## Data Understanding
The dataset resembles a real dataset and has many of the same challenges.  The columns were examined. What information does the dataset contain about customers? How many null values in each columns. Columns that can be used for segmentation were determined.

## Data Preparation
- Choosing which columns to use for the training was chosen since customers will be segmented using KMeans.
- Null values in the "Order payment type" column are filled with the same row as the previous row.
- Categorical variable is converted into dummy/indicator variables.

## Modeling
- Number of clusters where silhouette score remains constant number of customer segments should be selected
- When we look at the results, the number of customer segmentation should be 5
- 

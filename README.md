# Epicuriouser - A Machine Learning Project
Amy Koldeway, Sarah Cross

## Project Overview
We will use decision tree model to answer the question: Can an AI predict the rating of an Epicurious recipe?

## Data Source
We will be using the existing dataset of Epicurious recpices found on Kaggle (https://www.kaggle.com/hugodarwood/epirecipes).  Data set is for recipes created in 2005-2016.  If time allows we will scrape 2017-2019 data to add to dataset.

## Data Cleaning and Prep
We will peform the follwing cleaning steps:
- drop the Nan records
- remove outliers
- remove records with a zero rating that do not have a review count (this assumes 0 is valid rating score)

We will investigate proper way to identify the correct "features" for the decision tree model and perform addtion cleaning to ensure all recipes have features populated.

## Metrics to Evaluate Model
We will calculate the accuracy, recall, precision and f1 score of our model to determine its accuracy.  Based on those results, we will perform optimizations to increase the accuracy.

## Demonstrating Model
While jupyter notbook or colab may be where all the caculations happen, we will build a webpage that illustrates steps we took and results received for easy readability.

## Training the Model
Our Data set is around 30k records so we will use our own computers or colab - undecided at this point.

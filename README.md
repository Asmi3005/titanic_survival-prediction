# titanic_survival-prediction

## Overview  
This project involves building a logistic regression classifier to predict passenger survival on the Titanic based on various features such as age, gender, class, and ticket information. The project follows a structured workflow to ensure thorough analysis and accurate predictions.  

## Steps Performed  

1. **Understand the Problem Statement and Business Case**  
   - The objective is to classify whether a passenger survived or not based on given features, leveraging logistic regression for binary classification.  

2. **Import Libraries and Datasets**  
   - Loaded essential libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn`.  
   - Imported the Titanic dataset for analysis and modeling.  

3. **Perform Data Visualization – Part 1**  
   - Explored key features such as survival rates, age distribution, and gender impact using bar plots, histograms.  

4. **Perform Data Visualization – Part 2**  
   - Visualized correlations between features, passenger class survival rates, and the influence of other attributes using advanced visualizations.  

5. **Perform Data Cleaning and Feature Engineering**  
   - Handled missing values (e.g., filled missing `Age` values with median).  
   - Encoded categorical variables such as `Sex` and `Embarked`.  
   - Created new features such as `FamilySize` and simplified existing features like `Ticket`.  

6. **Train a Logistic Regression Classifier Model**  
   - Split the data into training and testing sets.  
   - Trained a logistic regression model using the `scikit-learn` library.  

7. **Evaluate a Logistic Regression Classifier Model**  
   - Evaluated the model using metrics like accuracy.  
   - Analyzed confusion matrix results and provided insights into the model's performance.  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  

## Key Outcomes  
- Successfully classified Titanic passenger survival with logistic regression.  
- Gained insights into the importance of features like gender, passenger class, and age.  



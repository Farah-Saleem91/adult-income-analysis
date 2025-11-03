<img width="299" height="168" alt="adult income" src="https://github.com/user-attachments/assets/971d13d0-f853-480f-af96-5dba8ab35b93" />


# Adult-Income-Analysis
## 📘 Project Overview

This project explores Adult Income Dataset, which predicts whether a person earns more than $50K per year based on demographic and work-related attributes.
The goal is to perform exploratory data analysis (EDA), data preprocessing, and clustering, followed by visualizations that reveal income patterns.

## 🎯 Objectives

- Understand relationships between demographic features (e.g., age, education, occupation) and income level.
- predict income level based on different features using supervised machine learning
- Apply K-Means clustering to uncover natural groupings in the data.
- Visualize trends and insights from both numerical and categorical features.

## 🧰 Tech Stack
- Languages: Python

- Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn.

- Modeling Techniques: Random Forest for supervised ML, Kmeans for unsupervised ML

- Tools: Google Colab, GitHub.
  
## 📊 Data Information
- Data Source: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset
- Dataset has 48842 records and 15 features
- Data Dictionary
<img width="1873" height="498" alt="Screenshot 2025-11-02 170235" src="https://github.com/user-attachments/assets/54696f8b-0255-473a-91a3-980ecf36ea87" />

## ⚙️ Steps Performed
1. Data Preprocessing

- Handled missing values and duplicates.

- Encoded categorical variables using OneHotEncoder and scaled numerical ones.

- Split data into train and test sets.

2. Exploratory Data Analysis (EDA) for each feature
3. Supervised machine learning to predict income category based on different features
4. Clustering using K-Means clustering on the scaled training data (X_train)
5. Predicted cluster labels for both training and test sets
6. Combined cluster labels with original features for modeling


## 🖼️ Visuals
### the relationship between Age and income
<img width="686" height="470" alt="age adult income" src="https://github.com/user-attachments/assets/744ced71-a778-45c4-98b5-3c791bd9a48e" />

- we can note that older individuals tend to have higher incomes, likely due to more experience or senior positions.
- The ≤50K group has a wider interquartile range (IQR) — ages are more spread out, meaning income ≤50K is common across a wider range of ages.

- The >50K group is more concentrated around ages 35–55, showing that high earners are typically in mid-career.

- Both groups have outliers, especially at higher ages (70–90). These represent older individuals still in the workforce, though relatively rare.

- The youngest individuals (around 17–20) are only in the ≤50K group, which makes sense since they’re early in their careers.

  
### Proportion of Income Levels by Occupation
<img width="1189" height="590" alt="occupation adult income" src="https://github.com/user-attachments/assets/7b2608f2-76fc-4be4-a568-a6cca20c9942" />

- For most occupations, the majority of individuals earn ≤50K, indicated by the taller blue bars. Only a few occupations show a relatively balanced or higher proportion of >50K earners.
- Exec-managerial and Prof-specialty occupations have the highest share of >50K earners, around 45–48%.
These likely represent higher-skilled or managerial positions with higher salaries.
- Handlers-cleaners, Priv-house-serv, Other-service, and Farming-fishing have almost everyone earning ≤50K. These are typically manual or low-skill jobs associated with lower income levels.
- Tech-support, Sales, and Protective-serv show somewhat more balance but still lean toward ≤50K.Suggests potential for upward income mobility depending on experience or sector.


## 📈 pemutation importance Visualization
<img width="559" height="547" alt="adult income permutation" src="https://github.com/user-attachments/assets/9c0add20-5849-4607-916a-862323217230" />

- Occupation is the most influential factor — meaning the type of job a person has has the strongest effect on whether their income exceeds $50K.

- Age follows closely, suggesting older individuals tend to earn more due to experience or career advancement.

- Hours-per-week is another strong factor — people working more hours are more likely to earn higher income.

## 📊 Key Insights

Individuals earning >50K are generally:

Older and more experienced.

Working longer hours.

Occupied in managerial or professional roles.

Clear separation between income groups can be partially captured through clustering.

## ✨ Author
- Farah Saleem
-  For any additional questions, please contact farah.saleem1991@outlook.com

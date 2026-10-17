## MachineLearning-Project
#Classification of Obesity Levels Based on Eating Habits and Physical Condition
Team: Cinthia Ochoa Torre, Christina Dames, Soumaya Tmane

## Data Set
The data comes from the publicly available UCI Machine Learning Repository dataset, "Estimation of Obesity Levels Based On Eating Habits and Physical Condition". We will investigate how eating habits and physical characteristics relate to obesity levels. The data contains 2,111 records and 16 features from individuals from Mexico, Peru, and Colombia. About 23% of the records are real, and the rest are synthetic. The target variable is NObeyesdad: the obesity-level label we are trying to predict, most likely derived from the Spanish Nivel de Obesidad (“obesity level”), since the data were collected in Latin America.

## Overview
Obesity is a complex, chronic disease defined by abnormal or excessive body fat accumulation that presents a health risk. It is associated with multiple lifestyle, eating, and physical factors. The goal of this project is to use machine learning techniques to develop and compare classification models that use eating habits and physical-condition variables to classify individuals into obesity-level categories. Our classification will be based on the following labels: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III. 

## Approach 
Preprocessing: categorical encoding, feature scaling, and a stratified train/test split
Models: Logistic Regression, Decision Tree, Random Forest, SVM/XGBoost
Evaluation: accuracy, precision, recall, F1-score (per class and overall), and confusion matrices

Built with Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.

## Limitations
Most of the dataset is synthetic, and it covers only three countries, so results may not generalize. This project only predicts obesity categories. It does not show that any habit causes obesity.

## References
F. M. Palechor and A. de la Hoz Manotas, "Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico," Data in Brief, vol. 25, p. 104344, 2019. https://doi.org/10.1016/j.dib.2019.104344
"Estimation of Obesity Levels Based On Eating Habits and Physical Condition" [Dataset], UCI Machine Learning Repository, 2019. https://doi.org/10.24432/C5H31Z (licensed under CC BY 4.0)
F. Pedregosa et al., "Scikit-learn: Machine Learning in Python," Journal of Machine Learning Research, vol. 12, pp. 2825–2830, 2011.
World Health Organization, "Obesity and overweight," fact sheet. https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight

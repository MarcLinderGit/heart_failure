# Predicting Heart Failure Mortality using Machine Learning

In this project, I explore the fascinating world of predictive analytics in healthcare by leveraging machine learning to predict the mortality risk of patients with heart failure.

### Project Overview

Cardiovascular diseases (CVDs) claim millions of lives annually, making them a global health concern. Heart failure, a common consequence of CVDs, presents an opportunity for early intervention. In this project, I utilize a dataset from Kaggle, encompassing 12 features such as age, anemia, and serum creatinine, to develop a machine learning model capable of predicting mortality based on these factors.

### Dataset Information

- **Number of Entries:** 299
- **Features:** Age, Anaemia, Creatinine Phosphokinase, Diabetes, Ejection Fraction, High Blood Pressure, Platelets, Serum Creatinine, Serum Sodium, Sex, Smoking, Time.
- **Target Variable:** DEATH_EVENT (0: No Death, 1: Death)

### Significance

As cardiovascular diseases remain a leading cause of death globally, there's a critical need for predictive models to aid in early detection. This project aims to contribute to this goal by training a neural network model to identify individuals at high risk.

### Model Training

I've trained a neural network model using features like age, ejection fraction, and serum creatinine. The model's performance is evaluated on a test set, and key metrics such as accuracy, precision, recall, and F1-score are considered to assess its effectiveness.

### Final Model Performance

After 100 epochs of training, the model achieved an accuracy of approximately 92.47% on the training set and demonstrated promising results on the test set with an accuracy of 73.33%. The model's precision, recall, and F1-score metrics are also provided to offer a comprehensive understanding of its performance.

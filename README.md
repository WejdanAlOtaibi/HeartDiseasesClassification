# HeartDiseasesClassification
I have found a dataset of patients with heart diseases, so I decided to build up a model that when given a patient it will predict and classyfy the patient if he/she has a heart disease or not.

The dataset consisted of patients of heart disease according to factors as such as: age, sex, and many nore.
Building up this model, I used many libraries and packages: Pandas for data analysis and reading into data, numpy for storing and operating on data, matplotlib.pyplot for plotting the data into graphes, seaborn for data visualization, and finally sklearn for building Machine Learning models.

The algorithms I used in this project are:
 - Sklearn Logistic Regression:  86.89% Accuracy
 - K-Nearest Neighbour:  88.52% Accuracy
 - SVM Algorithm: 86.89% Accuracy
 - Naive Bayes Algorithm:  86.89% Accuracy
 - Decision Tree Algorithm: Accuracy of 78.69%
 - Random Forest Classification: Accuracy of 88.52%
 
The data contained

 - age - age in years
 - sex - (1 = male; 0 = female)
 - cp - chest pain type
 - trestbps - resting blood pressure (in mm Hg on admission to the hospital)
 - chol - serum cholestoral in mg/dl
 - fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
 - restecg - resting electrocardiographic results
 - thalach - maximum heart rate achieved
 - exang - exercise induced angina (1 = yes; 0 = no)
 - oldpeak - ST depression induced by exercise relative to rest
 - slope - the slope of the peak exercise ST segment
 - ca - number of major vessels (0-3) colored by flourosopy
 - thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
 - target - have disease or not (1=yes, 0=no)
 
 Wishing good health to heart patients 

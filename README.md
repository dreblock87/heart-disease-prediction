# Cleveland Heart Disease

The goal of this project is to explore the Cleveland Heart Disease dataset and use machine learning to predict whether a patient has heart disease. 

## Data
This database from UCI Cleveland originally contained 76 attributes, with the final dataset containing only 15 attributes.
Experiments with the Cleveland database have concentrated on simply attempting to distinguish the presence of heart disease.

Source: [UCI Cleveland Heart Disease](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
    * Value 1: typical angina
    * Value 2: atypical angina
    * Value 3: non-anginal pain
    * Value 4: asymptomatic
4. restbp: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
    * Value 0: normal
    * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. maxhr: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
    * Value 1: upsloping
    * Value 2: flat
    * Value 3: downsloping
12. mv: number of major vessels (0-3) colored by flourosopy
13. thal: thallium heart scan 
    * Value 3: normal
    * Value 6: fixed defect
    * Value 7: reversable defect
14. diagnosis: severerity of heart disease (angiographic disease status)
    * Value 0: Absent
    * Value 1: Level 1 
    * Value 2: Level 2 
    * Value 3: Level 3
    * Value 4: Level 4
15. disease: heart disease
    * Value 0: No 
    * Value 1: Yes

## Analysis
The analysis will be broken up into two sections. The first section will use exploratory data analysis (EDA) to gain insights into the dataset, discover any structures within, extract variables that are important, detect any outliers or anomalies, and determine attributes should be used for the classification model. 

### Exploratory Data Analysis (EDA)

![alt text](https://github.com/dreblock87/ClevelandHeartDisease/blob/master/Images/Barchart.png "Logo Title Text 1")

![alt text](https://github.com/dreblock87/ClevelandHeartDisease/blob/master/Images/Pairplot.png "Logo Title Text 1")

### Classification

The second section will utilize a Decision Tree, which is a classification algorithm of supervised learning. The Decision Tree will use a two-step process which involves learning and predicting whether a patient has heart disease or not. 

![alt text](https://github.com/dreblock87/ClevelandHeartDisease/blob/master/Images/Decisiontree.png "Logo Title Text 1")


## Packages
  * Pandas (data structures and data analysis)
  * Seaborn (data visualization)
  * Matplotlib (data visualization)
  * Numpy (computing)
  * Scikit-learn (data mining and data analysis)
  

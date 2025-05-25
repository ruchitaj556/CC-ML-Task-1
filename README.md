# CC-ML-Task-1
This repository contains the solution of task 1.


**Level 1**
1. Created the histograms for the three levels to determine the counts of each of the values.
2. Created a correlation heatmap to analyze the correlation of the three features with other attributes.
3. As a conclusion from the insights drawn from the visualizations, following guesses were made by me:
   a. Feature_1 : **age**
   b. Feature_2 : **studytime**
   c. Feature_3 : **partytime**
4. The column name were renamed with the respective guesses.


**Level 2**
1. Found the datatypes of all the Columns.
2. Found out the columns with missing values.
3. Replaced the missing values in categorical columns with mode and null.
4. Replaced the missing values in numerical values with median.


**Level 3**
Following are the questions and thier insights:

**Q1** : Does the address(urban or rural) of the student affect the tendency of higher education?
**->** : Students residing in urban areas are most likely to pursue higher education.

**Q2** : Does weekday alcohol consumption affect the grades of the students?
**->** : Higher weekday alcohol consumption is associated with lower and more varied final grades.

**Q3** : Does number of school absences affect grades?
**->** : Students with less or no absences have relatively higher grades than those with more number of absences.

**Q4** : Is there a correlation between studytime and grades?
**->** : There is no regular trend, but students with studytime 3 and 4 have higher grades than those with 2 and 1.

**Q5** :  Are students with higher grades romantic?
**->** : Students with higher grades are not romantic.


**Level 4**
1. Encoded the data in categorical columns.
2. The target column (romantic) was split from the dataset.
3. Dataset was split into train set and test set.
4. Classifiers such as decision trees, random forests and logidtic regression were used.
5. Best accuracy of 68% was obtained with logistic regression pridicting **"not in relationship"**.


**Level 5**
1. Used SHAP for two students, one predicted "NO" and one "YES".
   a. for student who predicted "NO":
      Features such as health, absences, famsup, nursery, Dalc, etc. contribute positively to the prediction. Partytime and other 23 features contributed 
      negatively to the prediction.
      Model output is positive, so the prediction is correct (model favours the decision).

   b. for student who predicted "YES" :
      Most of the features contribute negatively to the prediction. Only sex, G3 and freetime contribute positively.
      Model output is negative, so the prediction is incorrect (model does'nt favour the decision).


Name : **Ruchita Satish Jadhav**
Roll no. : **240103092**
Department : **Mechanical Engineering**

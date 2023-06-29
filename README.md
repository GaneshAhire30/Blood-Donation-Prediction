# Blood-Donation-Prediction
## INTRODUCTION OF PROJECT :-
 **Blood transfusion saves lives - from replacing lost blood during major surgery or a serious injury to treating various illnesses and blood disorders. Ensuring that there's enough blood in supply whenever needed is a serious challenge for the health professionals. According to WebMD,"about 5 million Americans need a blood transfusion every year". Our dataset is from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive. We want to predict whether or not a donor will give blood the next time the vehicle comes to campus in March 2007**
 ### Attribute Information :-
 **1.Unnamed:0 :** 
  * This column represents the donor's unique ID.


**2.Months since Last Donation :** 
  * This is the number of months since this donor’s most recent donation.


**3.Number of Donations :** 
  * This is the total number of donations that the donor has made.


**4.Total Volume Donated (c.c.) :** 
  * This is the total amount of blood that the donor has donated in cubic centimetres.


**5.Months since First Donation :** 
  * This is the number of months since the donor’s first donation.


**6.Made Donation in March 2007 :** 
  * A binary variable representing whether he/she donated blood in March 2007 (1 stands for                                         donating blood; 0 stands for not donating blood)
## Dependencies :-
1. import pandas
2. import numpy
3. import seaborn
4. import matplotlib
5. import sklearn
## Description :-
**Use Python to explore data related to blood donors and we want to predict whether or not a donor will give blood the next time when the blood donation will be organised.**

  * This process will be done using a Jupyter Notebook.
  * The code should run w/o errors.
  * Appropriate use of
     * data structures/types
     * loops/conditional statements
     * Packages
     * functions
     * coding practices (i.e. Docstrings, comments, variable names & general readability)
     
  * Analysis
     * Pose questions about the data
     * Inspect the structure of the original data (very important)
     * Clean the data
     * Answer questions about the data using descriptive statistics
     * Visualize the data (using plt and seaborn)
     * Perform additional exploratory analysis
     * Consider where data analysis can be applied to other fields.
     
  * Feature Engineering
     * Using domain knowledge of the data to create features that make machine learning algorithms work.
  * Machine Learning
     * Use of LogisticRegression,Support Vector Machine, Decision Tree , Random forest, KNN, XGBClassifie classifiers.
### Performance metrics :-
* Machine Learning Classifiction model requires different metrics for evalution based on the data.
To measure the performance of our algorithms, we have used the F1 score which balances the precision and recall of a classifier and ROC AUC score.
## Conclusion :-
**Blood donation is significant for saving lives of people who lost large amounts of blood. An accurate prediction of the future supply of blood help to take the right action to save people lives. In this project, I created different classification models to predict whether or not a blood donor will give blood in future. Then, I used parameter tuning to improve the models. Logistic Regression as the best model for our dataset its giving us the AUC score of 0.8511. Logistic Regression classification algorithm gave the best accuracy (85%).**



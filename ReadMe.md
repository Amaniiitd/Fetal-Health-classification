**Libraries** :

1) numpy 
1) seaborn
1) pandas
1) matplotlib
1) sklearn

**Command line method for installing the libraries in python**:

1) For numpy: pip install numpy
1) For seaborn: pip install seaborn
1) For pandas: pip install pandas
1) For matplotlib: pip install matplotlib
1) For sklearn: pip install sklearn

**Models implemented for prediction**:

1) Logistic regression
1) Decision tree
1) Random Forest 
1) Naive Bayes classification
1) MLP
1) SVM 

**How to run .py file on IDLE**:

- Load the data set by changing the address given in the following command

pd.read\_csv(“location of data file in pc”)

- Then run the code.

**Preprocessing**:

- We removed 16 duplicate rows; removing these rows prevented our model from getting biased and generalized.
- We performed ( “analysis of variance” ) ANOVA F- test for feature selection. This method helps us remove the features independent of the target value. This method is useful when the data set is a mix of categorical and numerical features.
- 6 features removed were:-  histogram\_number\_of\_peaks, histogram\_number\_of\_zeroes, histogram\_tendency, histogram\_min, fetal\_movement, severe\_decelerations.
- Standardized the data to maintain a general distribution for the feature data values 
- Used a train-test split with a 7:3 ratio.



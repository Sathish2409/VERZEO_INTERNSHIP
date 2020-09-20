# VERZEO_INTERNSHIP_MINOR_PROJECT
Dataset <br/>
Red Wine Quality Dataset from kaggle-https:// www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009<br/>
Instructions:-<br/>
1. Import the dataset.<br/>
2. Data quality check:<br/>
  a. Check if null values are present. If there are, drop those rows.<br/>
3. Exploratory Data Analysis: <br/>
  a. Univariate Analysis:<br/>
    i. Draw a minimum of 5 histograms .<br/>
    ii. Draw boxplots for each numerical columns.<br/>
  b. Bivariate analysis: <br/>
    i. Draw a minimum of 5 scatter plots<br/>
4. Modelling:<br/>
  a. Split the dataset using “train-test-split” function. <br/>
  b. Apply KNN classification on “quality” column of the dataset. Select the appropriate features <br/>
  c. Apply logistic Regression on “quality” column of the dataset. Select the appropriate features <br/>
  d. Predict on the test set. e. Find out the accuracy.
  
# VERZEO_INTERNSHIP_MAJOR_PROJECT
1. Load dataset from - https://covid.ourworldindata.org/data/owid-covid-data.csv<br/>
2. Subset only those rows that have “India” in the “location” column(This subsetted
dataframe has to be used for modelling)<br/>
3. Handle Missing values:<br/>
a. If there are null values in continuous numerical column, replace the null values by
the mean of that column<br/>
b. If there are null values in ordinal numerical column, replace the null values by the
mode of that column<br/>
c. If there are null values in categorical column, replace the null values by the mode
of that column<br/>
d. If more than 50%the values in a column are null, then drop that entire column<br/>
4. Univariate Analysis:<br/>
a. Draw histograms of 10 feature columns<br/>
b. Find mean, median and mode of each column<br/>
5. Bivariate Analysis:<br/>
a. Draw scatter plots of target column versus 10 features<br/>
b. Draw line plots of target column versus 10 features<br/>
6. Convert date column to ordinal<br/>
7. Drop useless categorical columns, and convert useful categorical to numerical by
labelencoder<br/>
8. Select “total_cases” column as the target variable<br/>
9. Select the other columns as the features(NOTE: the “date” column has to be
compulsorily in the features)<br/>
10. Perform train-test split<br/>
11. Modelling:<br/>
a. Linear Regression<br/>
b. Random Forest Regressor<br/>
12. Get accuracy<br/>
13. Predict Total case for a new date<br/>

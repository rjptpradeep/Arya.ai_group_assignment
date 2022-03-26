
# Imported necessary library
# Loaded the train data set
# EXPLORATRY DATA ANALYSIS :
 Checked for numbers of features present in data set. There were total 3910 records and 59 features of which 58 were independent features and 1 was dependent featues  with class "0" and "1"
 
 Checked for data types of all features.
 
 Checked for mean, std, min, 25%, 50%, 75% and max values of all features.
 
 Checked for missing values
 
 Checked for number of "0" and "1" class share in Y feature.
 
 Performed univriate and bivariate analysis on data.
 
 Plotted box plot and created a function to check wheather there was any outliers in data set.
 
 Plotted heatmap to see relation between independent features.
 
 Analysed the distribution of y class with independent features and found that "Unnamed :0" had no effect on dependent featues so we dropped that features from dataset.
 
# Initialized three machine learnings algorithms and hypertuning
# Validation 
 Performed kfold validation on data and found which algorithm performing best
# Model creation
 Created model by training LogisticRegression with train data
 
 Predicted the class outcomes of test data.

# Credit Risk Analysis
Loan Approval Model that gives a prediction whether or not a certain loan applicant should be accepted. Depending on several attributes, the model should specify wether the applicant has a bad or a good creditability. And so, the bank managment can have an idea wether or not it should accept the applicant's loan request.

# Data Cleaning and Preprocessing
Attributes are mixed, there is nominal, ordinal and quantitative attributes.
Dropping attributes with low variance.
Checking for outliers within the quantitative attributes.
There are outliers that need to be removed in the numerical attributes.
Some of the ordinal attributes don't have the right values and need to be replaced.
Splitting the dataset into training and testing sets.
Nomrmalizing the training and testing sets' quantitative attributes.
Checking for correlations for the different quantitative and the class attribute.
Dropping attributes with the lowest correlation to the class attribute.
Creating dummy variables for the nominal attributes.
Last check to see if the class attribute has imbalanced values.
Defining functions for Confusion Matrix and Metrics (for Precision, Recall, and F1- score)

# Applying different ML algorithms
SVM -Logistic Regression
KNN
Random Forest

# Conclusion
Since the bank does not want to lose money giving applicants who won't pay the loan back, then the Recall is the most important parameter for us to be choosing our model. Random Forest had the highest Recall, and at the same time it had the highest accuracy among all the other algorithms.

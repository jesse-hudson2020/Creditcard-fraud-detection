# Creditcard-fraud-detection
A Logistic regression model is used for modeling the outcome probability of a class (fraud/not fraud) on a set of test data (creditcard transactions)
The Residuals vs. Leverage plots help to identify influential data points in your model. Outliers can be influential, though they don’t necessarily have to be and some points within a normal range in your model could be very influential (Cook's distance defines the threshold).
The normal qq plot helps to determine if our dependent variable is normally distributed by plotting quantiles (i.e. percentiles) from our distribution against a theoretical distribution. If our data is normally distributed, it will be plotted in a generally straight line on the qq plot.
A Receiver Optimistic Characteristics (ROC) curve is used to asses the performance of the model (As close as possible to 1 is good)
Note: 100% sensitivity = (no false negatives) and 100% specificity = (no false positives)
Next, a decision tree algorithm is generated to plot the outcomes of a decision
The first neural network we will generate is an artificial neural network (ANN)that allows for a model that is able to learn the patterns using the historical data and are able to perform classification on the input data (They are a form of machine learning algorithm that is modeled after the human nervous system)
Finally, using Gradient Boosting (GBM) the weak models from the decision trees can be combined to generate a better (strong) model
These outcomes are basically a consequence through which we can conclude as to what class the object belongs to (classify and generate clusters using dendrograms)
Note: The data was split into two groups, and we set a threshold as 0.5, that is, values above 0.5 will correspond to 1 and the rest will be 0
Gradient Boosting is a popular machine learning algorithm that is used to perform classification and regression tasks. This model comprises of several underlying ensemble models like weak decision trees. These decision trees combine together to form a strong model of gradient boosting (boosting).

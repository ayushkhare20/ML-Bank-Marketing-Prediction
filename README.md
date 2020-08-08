# Bank-Marketing-Prediction
Read in the file and got basic information about the data, including numerical summaries in which
-	Describe the pdays column, made note of the mean, median and minimum values.
-	Describe the pdays column again, this time limiting myself to the relevant values of pdays and finding How different are the mean and the median values.
-	Plotting a horizontal bar graph with the median values of balance for each education level value.
Finding Which group has the highest median.
-	Making a box plot for pdays to find out any outliers
The final goal is to make a predictive model to predict if the customer will respond positively to the
campaign or not. The target variable is “response”.
First,I perform bi-variate analysis to identify the features that are directly associated with the target variable.
-	Convert the response variable to a convenient form
-	Make suitable plots for associations with numerical features and categorical features’
And finding out the features about the previous campaign data useful and Are pdays and poutcome associated with the target.
If its yes, and if i plan to use them – how do i handle the pdays column with a value of -1 where the previous campaign data is missing. Explaining my approach and my decision.
Before the predictive modeling part, making sure to perform –
-	The necessary transformations for the categorical variables and the numeric variables
-	Handle variables corresponding to the previous campaign
-	Train test split
Predictive model 1: Logistic regression
-	Making a predictive model using logistic regression
-	Use RFE to select top n features in an automated fashion (choose n as you see fit)
-	Using p values and VIF, get rid of the redundant features
-	Estimate the model performance using k fold cross validation
-	finding what is the precision, recall, accuracy of your model.
-	Which features are the most important from your model.
Predictive model 2: Random Forest
 
-	Making a predictive model using random forest technique
-	Using not more than 50 trees, and control the depth of the trees to prevent overfitting
-	Estimate the model performance using k fold cross validation
-	What is the precision, recall, accuracy of your model?
-	Using the feature importance values from the Random Forest module, identify the most important features for the model
Compare the performance of the Random Forest and the logistic model –
-	Evaluate both models on the test set.
-	Which metric did i choose and why.
-	Which model has better performance on the test set.
-	Comparing the feature importance from the different models.

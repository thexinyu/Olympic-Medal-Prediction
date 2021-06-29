# Olympic-Medal-Prediction

Our project is focused around the Olympics, a longstanding tradition where the top athletes from around the world compete for Bronze, Silver, and Gold medals. 
Our goal is to determine the most influential factors in determining Olympic medal winners. We obtained a public dataset detailing 120 years of Olympic data, 
and transformed it to include the features: country, year, sport, event, population, GDP, age, BMI, height, weight, sex, and season. Our target variable is the 
type of medal earned including none, bronze, silver, or gold, and we are using a supervised classification machine learning model to predict what athletes will 
earn which medals. Additionally, we transformed our categorical data using Label Encoding and One Hot Encoding and scaled our data using log transformation, 
Min Max Scaler, and Standard Scaler. To balance our target variable, we resampled using random resampling and SMOTE. We then used K-Nearest Neighbors, Naive Bayes, 
and Decision Tree classifiers on our test data with feature selection and hyperparameter tuning. Our results showed a successful model using SMOTE sampling, kNN 
without feature selection nor hyperparameter tuning. We hope that our model is used in future research, and even for predicting the outcome of the 2021 Tokyo Olympics. 


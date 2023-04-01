# DSCI 100 Group Project: A Classification Analysis on Student Knowledge Level.
DSCI 100 - Section 002. Contributers: Tara Treagus, Teevint Prak, Michelle Benitez-Muller, Ayush Joshi

**Summary**<br>
In this report we aimed to predict the knowledge level of students from certain predictors. The available predictor candidates pertained to the study time, degree of repetition and exam performance of students. An effective model which determines user knowledge levels can be used to provide insight on students’ actual levels of material retention. Although test scores give insight on the comprehension of the student, they prove to not always be a complete representation of knowledge level. Exploration of student learning concluded that standardized tests are very limited in the information they can provide about a student's knowledge (Schneider, 2017). Therefore, we will statistically explore the predictors to determine which provide the most accurate estimate of student knowledge level.

**Data**<br>
The User Knowledge Modeling data set about students' knowledge of Electrical DC Machines, from the UCI Machine Learning Repository was used in this model. This is a multivariate data set, including five predictors and the target variable. Preliminary data analysis was performed to determine which predictors should be used to produce the most effective classification model.
Link: https://archive.ics.uci.edu/ml/machine-learning-databases/00257/Data_User_Modeling_Dataset_Hamdi%20Tolga%20KAHRAMAN.xls

**Method**<br>
This is a classification problem because the target variable is a non-numeric, categorical variable, whose class will be predicted. Regression models would not be effective in this setting as we are trying to assign an observation with a certain class, not predict its numerical value. Our classification model was built using the K-nearest neighbor algorithm (KNN). KNN works by finding the (K) number of points with the closest distance to a data point with unknown class. From the neighbouring points, the majority class classifies the new point as such. Our KNN classification model was trained and tuned using a training data subset, then evaluated on test data. The accuracy and confusion matrix from test data predictions determined the model’s ability to correctly predict the classes of new data.

**Objective**<br>
Our final model answers the question, what is the predicted knowledge level of a student on subject matter based on exam performance for goal objects and exam performance on related objects to goal object?

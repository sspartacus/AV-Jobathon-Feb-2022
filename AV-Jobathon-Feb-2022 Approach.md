# AV-Jobathon-Feb-2022 Approach

**Approach:**
First step was to import all the required libraries and also the train and test files into the 
notebook. By inspecting the data, we found out that there does not exits null values or data redundancies in train and test data set
therfore removing the requirement for data cleaning/data imputation. Our next step was to visualize the training dataset which resulted in our finding 
that content made for students will be very much beneficial to any video platforms since the engagement score
of students was greatest of the three. Next, since there exist 2 categorical features in our training dataset, i gave them tags using label encoding. 
Next step was seperating the train data into training and validation data where we split them into 3:1 ratio. Next, we imported different ML models and assessed them 
on the basis of r2_score as evaluation metric. We found that XGB regressor was the best among all the models chosen in order to predict engagement score.
Last but not the least, we submitted our  data predicted using XGB regressor
model keeping only the postive engagement scores in the sheet and removing the negative score if any.




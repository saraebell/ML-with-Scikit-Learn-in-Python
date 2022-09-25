# Survival-Prediction-Models-with-Scikit-Learn-in-Python
# Final Term Project
If we can see our future, we will certainly change how to live our lives today. However, we haven't invented the time machine yet. So instead of traveling to the future, we can first improve our ability to make predictions. With the skills we learned this semester in CS185C, we can see the trends and patterns in large amounts of data. We also know how to train Machine Learning models to make predictions. In this final term project, you are tasked to create a survival prediction model using data from patients with cardiovascular heart disease. Here is the link to the dataset: https://www.sjsu.edu/people/wendy.lee/docs/CS185C02-Sp21/heart_disease_clinical_data.csv

Your ML model will predict whether a patient will survive or die based on the following clinical features:

age: age of the patient (years)
anemia: decrease of red blood cells or hemoglobin (boolean)
high blood pressure: if the patient has hypertension (boolean)
creatinine phosphokinase (CPK): level of the CPK enzyme in the blood (mcg/L)
diabetes: if the patient has diabetes (boolean)
ejection fraction: percentage of blood leaving the heart at each contraction (percentage)
platelets: platelets in the blood (kiloplatelets/mL)
sex: woman or man (binary)
serum creatinine: level of serum creatinine in the blood (mg/dL)
serum sodium: level of serum sodium in the blood (mEq/L)
smoking: if the patient smokes or not (boolean)
time: follow-up period (days)
[target] death event: if the patient deceased during the follow-up period (boolean)
For more information, please check Table 1, Table 2, and Table 3 of the following paper. (Links to an external site.)

 

Project Deliverables

1. Create and answer at least 5 unique questions using different types of plots to help you understand the data. You can create additional categorical columns or reshape your data to help you understand the data.

2. Create a test set and a training set using the original dataset. 

3. Follow the steps that we use in Hands-ons 15 and 16 to prepare the data and pipeline for training a few ML classifiers that can predict a binary outcome (survive or dead). Use any strategy that you see fit. Use N-fold cross-validation to evaluate the performance of each classifier.

4. Create a ROC plot that shows all the trained ML classifier's performance. Select the best one for testing.

5. Test your best ML classifier using the test set.

6. Create a pre-recorded slideshow presentation video (5-10 min long) in which you explain the following:

how the data visualization help you with choosing certain strategies in developing the ML training pipeline
what strategy is used to create test/train data
what ML models are chosen, and why are they suitable for this analysis
the performance of all trained models (including an image of the ROC curve)
how is the performance of the best ML model using the test set. 
To wrap up, discuss the challenges you have encountered and/or any other thoughts you have about this project. 

7. A url to access the pre-recorded presentation video

Note: For the pre-recorded presentation, you can use any screen recording tools such as Loom (Links to an external site.), OBS Studio (Links to an external site.), or even just Zoom meeting with screen recording. Your recording will need to be uploaded to a cloud platform such as Youtube (unlisted) or Zoom cloud recording will automatically save the video in the cloud. 

8. The presentation slides (in PDF format)

9. All the Python code for Steps 1-5 should be contained in one Jupyter notebook. 

 

What to upload to Canvas on May 17, 2021 by 11:59 pm:

1. Python Jupyter notebook that contains your code.

2. Presentation slides in PDF format

3. A url to your pre-recorded presentation video.

 

Peer Evaluations (due on May 21, 2020 by 11:59 pm)

You will be assigned to evaluate three other student's project presentation. A Google form will be provided to you to give your feedback to each student.

 

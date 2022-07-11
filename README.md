# DiabetesPrediction


This model tells us whether a woman of atleast 21yrs old of Indian origin has  diabetes or not.

The data set used here is given by National Institute of Diabetes and Digestive and Kidney Diseases

The objective is to predict based on diagnostic measurements whether a patient has diabetes or not.

The factors that are considered are
   1. Pregnancies: Number of times pregnant
   2. Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
   3. BloodPressure: Diastolic blood pressure (mm Hg)
   4. SkinThickness: Triceps skin fold thickness (mm)
   5. Insulin: 2-Hour serum insulin (mu U/ml)
   6. BMI: Body mass index (weight in kg/(height in m)^2)
   7. DiabetesPedigreeFunction: Diabetes pedigree function
   8. Age: Age (years)
   
   
If the Outcome is 0,then the patient doesn't have Diabetes else the patient has Diabetes

I used supervised machine learning to predict whether a patient has diabetes or not.

K-Nearest Neighbours algorithm is used for the prediction with 5 nearest neighbors.The trained data set size is 80%  of the original dataset and the test data set size is 20% of the original dataset.

The accuracy is 70.77% using KNN-algorithm.

The confusion matrix is visualized using heatmap.

Values of

True Positive:29

True Negtaive:80

False Positive:30

False Negative:15


__TERMS AND THEIR MEANING:__

True Positive:Person has disease and predicted correctly

True Negative:Person doesn't has disease and predicted correctly

False Postive:Person doesn't has disease and predicted wrongly(that is predicted that person has disease)

False Negative:Person has disease and predicted wrongly(that is predicted that person doesn't has disease)

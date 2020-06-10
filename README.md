Task was to held EDA for further using dataset to predict math score.
Conclusions:
1. dataset had lots of NA
2. NA was filled with median, mode or changed to 'not_known'
3. outliers were deleted using IQR
4. variables to be used: age, absences, medu, fedu, mjob, studytime, failures, health, sex, address, schoolsup
5. binary variables should be encoded with LabelEncoder from sklearn.preprocessing
6. nominal variables should be encoded as dummy variables (drop_first='True')

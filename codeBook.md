#Variables definition

## Split data
x_train, y_train, x_test, y_test, sub_train, sub_test hold the downloaded Samsung data
    
##Aggregated data from train/test:
1. X: all numeric data for the patients
2. y: activity labels for each subject
3. sub: subject id's
    
# Descriptions
1. feature_names: names of each column in X
2. filtered_features: filtering the features that have 'mean' or 'std' in the column name
3. label_names: names of the levels in y, used to create y as a factor instead of numeric labels
    
## Combined
1. combo: combined X,y,sub data to tidy
2. means: summary (mean) per activity per subject

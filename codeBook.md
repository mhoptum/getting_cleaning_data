#Variables definition

    # Split data
    x_train, y_train, x_test, y_test, sub_train, sub_test hold the downloaded Samsung data
    
    #Aggregated data from train/test:
    X: all numeric data for the patients
    y: activity labels for each subject
    sub: subject id's
    
    # Descriptions
    feature_names: names of each column in X
    filtered_features: filtering the features that have 'mean' or 'std' in the column name
    label_names: names of the levels in y, used to create y as a factor instead of numeric labels
    
    # Combined
    combo: combined X,y,sub data to tidy
    means: summary (mean) per activity per subject

# gene_expression
Disease Classification Model with Gene Expression Data

### Data Cleaning
script: "Data Cleaning.R" 	
1. Remove features with zero or near zero variance	
2. Fill in NA values with k Nearest Neighbours	
3. Reduce multicollinearity by removing features with correlation higher than 0.7

### Feature Selection 
script: "Feature Selection.R"   
1. Prepare training scheme, 10-Fold CV    
2. Calculate feature importance with RandomForest   
3. Visualize the numbers of features selected by importance threshold   

### Compare Models
script: "Compare Models.R"    
1. Select features and prepare data frame      
2. Compare 9 different models   
3. ROC as metric to evaluate, compare performance among models   

### Optimization
script: "Optimization.R"    
1. Find optimal features for performance    
2. Find optimal parameter for performance   
3. Final model for test data

### Predict Test Dataset
script: "Predict Test Dataset.R"    
1. Import test dataset    
2. Prepare test dataset   
3. Predict disease with final model   

## Final Prediction
file: "testPrediction.txt"

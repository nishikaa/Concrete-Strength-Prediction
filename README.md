# Concrete-Strength-Prediction
Objective 
To predict the concrete strength using the data available in file concrete_data.xls. Apply 
feature engineering and model tuning to obtain 80% to 95% of R2score.
 
Resources Available 
The data for this project is available in file https://archive.ics.uci.edu/ml/machine-learningdatabases/concrete/compressive/. The same has been shared along with the course content.
Steps and Tasks: 
 
 Exploratory data quality report reflecting the following: 
1. Univariate analysis – data types and description of the independent attributes 
which should include (name, range of values observed, central values (mean and 
median), standard deviation and quartiles, analysis of the body of distributions / 
tails, missing values, outliers, duplicates
2. Bi-variate analysis between the predictor variables and between the predictor 
variables and target column. Comment on your findings in terms of their 
relationship and degree of relation if any. Visualize the analysis using boxplots and 
pair plots, histograms or density curves.
3. Feature Engineering techniques
a. Identify opportunities (if any) to extract a new feature from existing features, 
drop a feature (if required)
b. Get data model ready and do a train test split.
c. Check for higher degree attributes, should it be linear, quadratic or higher
degree? Use Polynomial Features (Consider degree 2 and 3).
 Creating the model and tuning it
1. Algorithms that you think will be suitable for this project. Use Kfold Cross 
Validation to evaluate model performance. Use appropriate metrics and make a 
DataFrame to compare models w.r.t their metrics.
(at least 3 algorithms, one bagging and one boosting based algorithms has to be 
there). (15 marks)
2. Techniques employed to squeeze that extra performance out of the model 
without making it over fit. Use Grid Search or Random Search on any of the two 
models used above. Make a DataFrame to compare models after hyperparameter 
tuning and their metrics as above. (15 marks)| Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited
 
Attribute Information:
Given are the variable name, variable type, the measurement unit and a brief description. 
The concrete compressive strength is the regression problem. The order of this listing 
corresponds to the order of numerals along the rows of the database.
 
 
Name -- Data Type -- Measurement -- Description
 Cement (cement) -- quantitative -- kg in a m3 mixture -- Input Variable
 Blast Furnace Slag (slag) -- quantitative -- kg in a m3 mixture -- Input Variable
 Fly Ash (ash) -- quantitative -- kg in a m3 mixture -- Input Variable
 Water (water) -- quantitative -- kg in a m3 mixture -- Input Variable
 Superplasticizer (superplastic) -- quantitative -- kg in a m3 mixture -- Input Variable
 Coarse Aggregate (coarseagg) -- quantitative -- kg in a m3 mixture -- Input Variable
 Fine Aggregate (fineagg) -- quantitative -- kg in a m3 mixture -- Input Variable
 Age(age) -- quantitative -- Day (1~365) -- Input Variable
 Concrete compressive strength(strength) -- quantitative -- MPa -- Output Variable

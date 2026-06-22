# LinearRegressionAssignment
# Explore the Dataset:
# Analyze the mobile price dataset to understand its structure, feature distributions, and relationships before model building.
# Perform the following:
# Inspect dataset shape, columns, data types, and missing values
* Imported CSV file
* using df.shape found there are 161 rows and 14 columns
* Inspected Shape,columns, data types, info,
* Using duplicated and isnull found missing and duplicate values
* There was no duplicate and missing value present in the data
# Generate statistical summaries for numerical features
* Manually printed statistical summary for numerical features using agg 
# Create a correlation heatmap focusing on Price
* Using corr matrix plotted heatmap
# Identify the top 4 features most correlated with Price
* Calculated Corr Matrix using it found beast 4 columns correlated with Price
* ram             0.896915, ppi             0.817614, internal mem    0.776738, RearCam         0.739538
# Plot scatter plots for these features against Price and analyze the relationships
* Plotted Scatter Plots
# Prepare the Data:
* Feature Selection: Using SelectKBest, f_regression prepared X and y
# Split the Dataset:
* Using train_test_split data has been splited to 80% for training and 20% for testing
# Build and Train the Model:
* Create a Linear Regression Model -Created model and fed it with Linear Regression. Also trained the model with X_train,y_train
# Predicting with model :
* Using y_pred predicted model with Testing data
# Evaluate the model’s performance using the following metrics:
* Calculated model Coefficient and model intercept
* Calculated R2, MAE, MSE


# OIBSIP_3
CAR PRICE PREDICTION WITH MACHINE LEARNING

The price of a car depends on a lot of factors like the goodwill of the brand of the car,
features of the car, horsepower and the mileage it gives and many more. Car price
prediction is one of the major research areas in machine learning. So if you want to learn
how to train a car price prediction model then this project is for you.

Explaination:
1. Data Loading and Checks:
- load the dataset from a CSV file using pd.read_csv.
- Check basic information about the dataset.
- Check for missing values.
- Check for duplicate rows.
- Check data types of columns.
- Print the first and last few rows of the dataset.
- Display the shape of the dataset.

2. Data Preprocessing:
- Use Label Encoding for the 'Car_Name' column.
- One-hot encode categorical variables ('Fuel_Type', 'Selling_type', 'Transmission') using pd.get_dummies.
- Convert the 'Selling_Price' column to numeric.
- Create a new feature 'Car_Age' based on the 'Year' column.
- Standardize numerical features ('Present_Price', 'Driven_kms', 'Car_Age') using StandardScaler. 

3. Feature Selection:
- Define features (X) and the target variable (y) based on the processed DataFrame.

4. Exploratory Data Analysis (EDA):
- Visualize the distribution of the target variable using a histogram.
- Visualize relationships between numerical features and the target variable using a pairplot.
- Visualize relationships between categorical features and the target variable using boxplots.
- One-hot encode categorical variables for correlation analysis.
- Visualize correlations between numerical features using a heatmap.

5. Data Splitting:
- Split the data into training and testing sets using train_test_split.

6. Model Building:
- Create a Linear Regression model using LinearRegression() from scikit-learn.
- Train the model using the training data (X_train and y_train).

7. Model Evaluation:
- Make predictions on both the training and testing sets.
- Evaluate the model using Mean Squared Error (MSE) for both training and testing sets.
- Evaluate the model using R-squared for both training and testing sets.

8. Visualization:
- Visualize the predicted vs. actual selling prices on the test set.
  
This provides a comprehensive approach to data analysis, preprocessing, exploration, model training, and evaluation for a car selling price prediction task.

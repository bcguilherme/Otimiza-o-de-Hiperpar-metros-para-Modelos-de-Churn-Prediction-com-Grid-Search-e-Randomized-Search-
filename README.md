# Tunning_na_pr-tica

# Hyperparameter Optimization

This repository contains an example of hyperparameter optimization for machine learning models using Python. The code addresses hyperparameter optimization for decision tree, random forest, and LightGBM models in a churn classification problem.

## How to Use this Code

1. **Loading the Data**: The code begins by loading data from the "churn_data.xlsx" file. Make sure you have the data in the correct format.

2. **Data Preprocessing**: Data is preprocessed, including type conversion, handling missing values, and creating dummy variables for categorical features.

3. **Train-Test Data Split**: The data is split into training and test sets to evaluate model performance.

4. **Grid Search for Decision Tree**: A Grid Search is performed to optimize hyperparameters for a decision tree. The tested hyperparameter is the maximum tree depth.

5. **Grid Search for Random Forest**: Next, a Grid Search is conducted to optimize hyperparameters for a Random Forest model. The tested hyperparameters include maximum tree depth and the number of estimators.

6. **Randomized Search for LightGBM**: Finally, a Randomized Search is performed to optimize hyperparameters for a LightGBM model. Hyperparameters include learning rate, number of leaves, minimum sample size, subsampling, and column size.

7. **Results**: The results of each optimization step are recorded in a DataFrame, and the best hyperparameters are highlighted.

## Prerequisites

Make sure you have the required Python libraries installed. You can install them using `pip`:


## How to Run the Code

Ensure that you have the data file "churn_data.xlsx" in the same directory where you run the code. The code is designed to optimize hyperparameters of machine learning models to solve a churn classification problem.

## Contributions

Contributions are welcome. Feel free to open issues or submit pull requests if you want to enhance the code or add more functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

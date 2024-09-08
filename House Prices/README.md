# **House Prices Prediction Kaggle Competition**

**Objective:**

The goal of this competition is to predict the sale price of houses based on various features. Dataset containing information about houses was provided. These includes number of bedrooms, living area, lot size, and other relevant attributes. The task was to build a predictive model that can accurately estimate the sale price of a house given its characteristics.

**Dataset:**

The dataset will include the following columns:

* **ID:** A unique identifier for each house.
* **SalePrice:** The target variable you'll be predicting.
* **...** (for a list of all the features, [click here](./data_description.txt))

**Evaluation Metric:**

The competition will be evaluated using the Mean Squared Error (MSE), if future, I plan to evaluate using Root Mean Squared Error.

**Submission:**

The submission is a CSV file containing two columns:

* **ID:** The unique identifier for each house in the test set.
* **SalePrice:** Your predicted sale price for each house.

**My approach to solving the problem:**

1. **Download the dataset:** Accessed the dataset from the competition page on Kaggle, see link [here](https://www.kaggle.com/code/alexisbcook/machine-learning-competitions).
2. **Explore the data:** Analyzed the dataset to understand the distribution of features, identify missing values, and identify potential correlations.
3. **Choose a modeling approach:** Select appropriate machine learning algorithms or techniques based on the nature of the data and the evaluation metric. In this case, I have used several models just for fun to see which one is most accurate.
4. **Train and evaluate the model:** Split the dataset into training and testing sets, train the model on the training data, and evaluate its performance on the testing data.
5. **Submit predictions:** Create a CSV file with your predictions and submit it to Kaggle.

**Additional Tips (future plans):**

* **Feature engineering:** Consider creating new features or transforming existing ones to improve model performance.
* **Handle missing data:** Impute missing values or remove rows with missing data.
* **Address outliers:** Identify and handle outliers that may skew your model's predictions.
* **Experiment with different models:** Try various algorithms and hyperparameters to find the best-performing model.



Thanks for reading :).

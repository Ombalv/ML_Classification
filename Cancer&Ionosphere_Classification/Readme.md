# Instruction of Implementing the Code of Group 2's Miniproject 1

**Authors**: Songyi Guan, Benton Qiu and Sai Ganesh

The Logistic Regression model predicts a binary class given a set of training data by calculating weights for each feature and implementing them to create a decision boundary.

Our model explores feature selection and addition through PCA, Mutual Information and non-linear dimension expansion as well as run-time and gradient descent thresholds.

## Organization
The blocks of entire of our project code is attached to the `code.zip` file, whose name is `code.ipynb`. Just directly upload it to Google Colab, modify two dataset file paths into your own file paths and directly run all of the code blocks. It will unveil the results, which encompass exact ***values***, ***figures*** and ***tables*** in result blocks.

# Instructions to Run:

1. Load data using Block 1 *Note file paths must be changed depending on your google drive.
2. Run each block in consecutive orders
3. Results should be printed in console after each run.
______________________________________________________________________________
Code Breakdown:

	Block 1 - Data Preprocessing:

		Loads datasets, removes useless features, maps classes, shuffles and splits dataset into test and train.

	Block 2- Logistic Regression Model

		Logistic Regression Model with classes "fit" to determine weights, "predict" to calculate outcomes, "accu_eval" to evaluate the accuracy and "confusion_matrix" to determine positives and negatives.

	Block 3 - Plain Logistic Regression:

		Determine baseline accuracy with standard dataset and confusion matricies.

	Block 4 - Plain Logistic Regression with K-Fold Cross Validation:

		Implements 10-fold cross validation with logistic regression, returns average over all folds and accuracy over each fold

	Block 5- Mutual Information and Polynomial Features:

		Calculates Mutual Information between each feature and the target variable and adds non-linear features and removes features based on the mutual information thresholds.

	Block 6 - Principle Component Analysis

		Determine best subset of features with K-fold and without K-fold analysis.

	Block 7 - Learning Rates and Iteratins Compared with Accuracy:

		Compares several different learning rates and iteration counts to the accuracy acheived, determines best learning rate and interation count.

Note these blocks are present for both Breast Cancer and Ionosphere Dataset!


_______________________________________________________________________________






# Instruction of Implementing the Code of Group 2's Miniproject 2

**Authors**: Songyi Guan, Benton Qiu and Sai Ganesh

The baseline Bernoulli Naive Bayes model is trained to predict a four-class text set given a set of training data.

Additional model are used for better performance

Our model explores several preprocessing techniques.

## Organization
The blocks of entire of our project code is attached to the `code.zip` file, whose name is `Mini Project 2 Group 2.ipynb`. Just directly upload it to Google Colab, modify training set file paths into your own file paths and directly run all of the code blocks. It will unveil the results, which encompass exact ***values***, ***figures*** and ***tables*** in result blocks.

# Instructions to Run:

1. Load data using Block 1 *Note file paths must be changed depending on your google drive.
2. Run each block in consecutive orders
3. Results should be printed in console after each run.
4. It may take some time to run the GridSearchCV method.
______________________________________________________________________________
Code Breakdown:

	Block 1 - Data Preprocessing:

		Loads datasets, lemmalization, stopwords, vectorization.

	Block 2- Proposed Approach

		Including BNB, LR, SVM, RF, KNN, Stacking Ensemble validated by gridsearch 10-fold cross validation and the performance of each models is shown in text blocks.
	
	Block 3- Testing

		Using aforementioned trained model to predict the given test set and save them as .csv files for further kaggle competition uploading.

_____________________________________________________________________________






**Approach used in this project is -** 

1) Data-preprocessing:
   1. all hyphan symbol deletion
	 2. all letter small-case

2) Basic Data-Analysis:
	  1. Listing statastical properties 
	  2. Finding missing values
	  3. replacing missing values
	  4. Correlation
	  5. Detecting outliers
	  6. Handling Outliers

3) Feature Engineering for the baseline model:
	1. forest.feature_importances 

4) Selecting Algorithm for Baseline-Model:
	1. KNN
	2. Logistiv_Regression
	3. AdaBoost
	4. Gradient_Decent
	5. Random_Forest

5) Fit and the training dataset for baseline model:

6) Testing the model with test_matrix: 
	1. accuracy & roc_auc_score() 
	2. Baseline-Model accuracy (AdaBoost & GradientBoost performed best)

7) Optmising the existing accuracy: 
	1. Cross-Validation Techniques (Check the overfitting issue)
	2. HyperParameter tuning 
		a. GridSearch Parameter Tuning
		b. Random Search Parameter Tuning

8) feature transformation as well as implementing a voting classifier:
	1. Log transformation of features
	2. Voting-based ensembel model

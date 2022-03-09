# Text_Classification

You can download the python and executes it with different text classification algorithm by passing parameters

python3 bbc.py -h 

Display all the different types of algorithms that can be executed.

By default it takes svc algorithm




python3 bbc.py --algorithm svc : uses SVC algorithm


python3 bbc.py --algorithm nv : Uses Naive Bayes algorithm


python3 bbc.py --algorithm rf

Above command does the text classification by taking Random Forest as the training algorithm


Output:

Drive is not mounted so picking data from github url

Text processing...

Cleaning done

Shape of Train Set is  (1780, 4)

Shape of Dev Set is  (222, 4)

Shape of Test Set is  (223, 4)



Training with Random Forest as the model

Count Vectorizer: 
	 
	 Reducing features from (1780, 7807) to (1780, 100) using chi2
Tfid Vectorizer(Uni-gram): 
	 
	 Reducing features from (1780, 11369) to (1780, 100) using chi2
Tfid Vectorizer(Bi-gram): 
	 
	 Reducing features from (1780, 5433) to (1780, 100) using chi2 


Combined features are of shape (1780, 300)


Results for Random Forest on DEV set is with k = 100 
-----------------------------------------

Precision: 0.943
Recall: 0.943
F1-Score: 0.943
Accuracy: 0.941


Training with Random Forest as the model


Count Vectorizer: 
	 
	 Reducing features from (1780, 7807) to (1780, 500) using chi2
Tfid Vectorizer(Uni-gram): 
	 
	 Reducing features from (1780, 11369) to (1780, 500) using chi2
Tfid Vectorizer(Bi-gram): 
	 
	 Reducing features from (1780, 5433) to (1780, 500) using chi2 

Combined features are of shape (1780, 1500)

Results for Random Forest on DEV set is with k = 500 
-----------------------------------------

Precision: 0.947
Recall: 0.949
F1-Score: 0.947
Accuracy: 0.946


Training with Random Forest as the model


Count Vectorizer: 
	 
	 Reducing features from (1780, 7807) to (1780, 1000) using chi2
Tfid Vectorizer(Uni-gram): 
	 
	 Reducing features from (1780, 11369) to (1780, 1000) using chi2
Tfid Vectorizer(Bi-gram): 
	 
	 Reducing features from (1780, 5433) to (1780, 1000) using chi2 

Combined features are of shape (1780, 3000)

Results for Random Forest on DEV set is with k = 1000 
-----------------------------------------
Precision: 0.955
Recall: 0.956
F1-Score: 0.955
Accuracy: 0.955


Training with Random Forest as the model

Count Vectorizer: 
	 
	 Reducing features from (1780, 7807) to (1780, 2000) using chi2
Tfid Vectorizer(Uni-gram): 
	 
	 Reducing features from (1780, 11369) to (1780, 2000) using chi2
Tfid Vectorizer(Bi-gram): 
	 
	 Reducing features from (1780, 5433) to (1780, 2000) using chi2 

Combined features are of shape (1780, 6000)

Results for Random Forest on DEV set is with k = 2000 
-----------------------------------------
Precision: 0.965
Recall: 0.966
F1-Score: 0.966
Accuracy: 0.964


Results for Random Forest on Test set is
-----------------------------------------
Precision: 0.952
Recall: 0.956
F1-Score: 0.954
Accuracy: 0.955






# Titanic_LN_AnyaMit
FrontlineAnalytics_KNearestNeighbor_Model for Titanic 

Download original train and test data from https://www.kaggle.com/c/titanic
Clean the dataset as follows (Before =data as downloaded, After = cleaned):

Data Conversion for test and train (before running the model)		
	Before	After
Key	Male	0
	Female	1
Age		
	NULL	29
	*All other values adjusted to nearest whole value	
	*29 is the mid point between median and mean
Embarked		
	S	1
	C	2
	Q	3
		
Fare	0	14.5
	*Fare adjusted to nearest whole value	
	* 14.5 is the average fair
		
Cabin	(Cabin numbers were ignored)
  A	1
	B	2
	C	3
	D	4
	E	5
	F	6
	G	7
	T	8
	None	0

System: Use the Frontline Analytics Software for Excel - XLMiner AddIn
Run the Classification Model for Linear Regression

# Assignment 1
- Enable **logging** so that all printouts from your program goes directly to a log file named
**logfile.txt** which you also need to submit alongside your source code.
- Read **A.csv data.** It's a dataset about a counterfeit bank note detection task. And, ofcourse it's a **binary classification task**, where 0: not a counterfeit note, and 1: a counterfeit note. Load data into your programming workspace.
- Separate dependent variable y as the counterfeit column, and rest of the variables as independent variables (as X).
- Split the dataset, i.e., the (X,y) into training (50%) and test (50%).
- Load the scaler object from **scaler.joblib**. It's already fit to a bunch of training samples. So, don't worry about fit it again. Instead, you may want to use the following lines to use the already fitted scaler object to transform both training and test set. And, do not scale the dependent variable/feature (i.e., y which is the target column counterfeit).
  

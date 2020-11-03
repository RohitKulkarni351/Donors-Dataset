# Donors-Dataset
DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. With the use of ML we are essentially 
performing classification :- Whether to approve the proposal(1) or to reject it(0)


Applied various ML models on Donors Choose dataset like tSNE, Naive Bayes, Logistic Regression, SVM, Clustering etc. 
* Performed Exploratory Data Analysis
* Data Loading
* Data Cleaning
* Data Preprocessing
* Data Modeling
* Metric for performance measurement

Basic Flow of Notebooks:-
1.  Reading the data
2. Preprocessing the data (Text & Categorical Data)
3. Splitting the data into train, test and cross-validation
4. Preparing data for modeling
  a) Categorical - One Hot Encoding
  b) Text - BoW, Avg W2V, TFIDF W2V Vectorizations
  c) Numerical - Standardization, Normalization
5. Concatenating above features
6. Applying the model
  a) Importing the model
  b) Find the right parameter value by gridsearch or randomsearch
  c) Train the model with the suitable value of parameter
  d) Make a confusion matrix for performance evaluation

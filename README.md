# project-3

Multiple Disease Prediction 

#Part_1 
(i) Handled Three Datasets - df1 (India Liver Disease),df2 (Kidney Disease),df3 (Parkinsons Disease)
(ii) Preprocessing 
    Handling Missing Values
    Filling Missing Values Based on 
    if the column has a normal distribution and no outliers use - mean
    else: use the median

#Part_2
(i) Define categorical and numerical columns in each dataset
(ii) Encoding categorical data

#Part_3
(i) scale numerical Columns
(ii) train three datasets using Logistic Regression and SVM Classifier because those three dataset target column has
    classify
(iii) all three datasets get an unbalanced dataset and df1 does not get accuracy
(iv) so using Robust Scaling
(v) Use the SQL method to find Outliers and trim the df1 dataset
(vi) Use the [SMOTE] Method to balance all Dataset
(vii) all datasets get an accuracy of more than 80% and balanced dataset

#Part_4

(i) Create Machine Learning Automatic FrameWork Using Streamlit Application
(ii) connect three datasets 
(iii) then select the target column and give the result as
     
     #dataset type 
      * balanced or unbalanced dataset
      if a balanced dataset shows only Accuracy
      otherwise unbalanced datasets shows - precession,recall,f1_score
      
      #Numerical
      * analyze target column has Continous or discreet
      * if Continous use (Linear Regression, Polynomial Regression, Ridge Regression, Lasso Regression, SVM Regression)
      * else: use Discret ( Decision Tree Regression, Random Forest Regression (Bagging type), XG Boosting 
       Regression(Boosting type), Nave Bayes Regression and SVM Regression )
       
       #Categorical
       * Analyze Column type has Binary or Multiclass
       * if Binary use ( Logistic Regression, SVM Classifier)
       *else Multiclass (Decision Tress Classifier, Random Forest Classifier, XG Boosting Classifier, Nave Bayes 
      Classifier and SVM Classifier

  #Part_5

  #EDA already After Handled Missing Values Before of encoding
  (i)EDA For Multiple Disease Prediction
  (ii) EDA Done by All three Dataset using Univariate, Bivariate(Countmap) and Multivariate(Heatmap)

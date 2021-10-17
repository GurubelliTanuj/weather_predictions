# weather_predictions
In this Weather_prediction project ,here i am predicted future maximum temparature using past temparature values. 
here i used pythin language to do prediction.
libraries which i used for predictions are :- 
    import pandas
    import numpy 
    import warnings from sklearn.linear_model 
    import LinearRegression from sklearn.model_selection 
    import train_test_split from sklearn import metrics 
    import matplotlib.pyplot
    import seaborn 
Here is the steps which i applied on the data to get prediction
   1. started at first i imported the libraries after that to read the csv file ; i wrote pd.read_csv() 
   2. after that according to problem statement i checked for null values using isna().apply(pd.values_count) after filling the null values using fillna()
   3. then splitted my train data and test data after that by importing the linear Regressin model created object and then using this model object trained the model to calculate       linear regression,after that predicted the maximmum temperature values using previous Temperature values. 
   4. then find the coefficient using model.coeef_; finding the interccept model.interccept_;
   5. compared actual value with the predited values;after that to find the accuracy using the MSE,R2,Adjusted R2 and after that  i plot the graph.

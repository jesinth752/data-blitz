# data-blitz

<--- Housing price Prediction -->

# Package Requirements
   --> pandas
   --> numpy
   --> seaborn
   --> sklearn
 # pandas
      --> pandas are dataframes performing manipulation and data analysis. 
      --> used to read csv files into dataframes.
 # numpy
       --> numpy is used to working with arrays.
 # seaborn 
       --> This library used to visualize.
       --> provides bulit-in datasets.
 # sklearn
       --> Simple and efficient tools for predictive data analysis
       --> sklearn metrices such as confusion matrix, accuracy score , MSE (Mean Sqaured error) 
       
   
 # Providing Alternative solution
       
 If You  are Calculating Accuracy rate for any one of the regressor don't conclude with one solution,Try to provide alternative solutions
 with different regressors.
 Use more regressor 
 
 In My Case I have used Kneigborsregressor which gives as 27% accuracy score, So I moved on to Linear Regression and that gives 63% accuracy rate 
 and I continued with other regresssors.
 
 LGBM regressor shows higher accuracy compared to others.
 
 # Handling Missing values 
 
 In this case,I got 270 Null values in total bedrooms field , you can use any of these following methods to solve or Handle missing 
 values
 
  isnull()
  Notnull()
  dropna()
  fillna()
  replace()
  interpolate()
  
 In this,I have used fillna() for solution,Taking mean value for total bedrooms and then use fillna() method automatically fills the missing value in
 total bedrooms
 
 # Encoding the field
 In this, The field ocean proximity is categorical column can be didived into different fields according to the data.
 Encoding non numerical to numerical for further process.
 
 
 

            
       
       

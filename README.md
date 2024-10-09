This project is all about Mobile Price Prediction using supervised Machine Learning wtih Featuer Extraction.
I begin this project by loading Mobile Price dataset with the help of Pandas library.
As i observed the dataset I started Preprcessing by handling missing values,outliers and categorical data using Label encoder .
After data preprocessing I perform feature extraction to identify the most relevant features that strongly affect the price of mobile phones.
Using statistical methods, visualizations, or feature importance techniques (e.g., correlation analysis, feature selection, or dimensionality reduction) to narrow down the list of important features.
After featuer extraction my dataset is ready to split in TRAIN AND TEST dataset to develop a machine learning model for price prediction.
Iuesd Regression Algorithms because price is continuous value so i use Linear Regression ,Random Forest Regression and Support Vector Machine.
Then I evaluate the model's performance using appropriate metrics (e.g., mean absolute error, root mean squared error,r2 score) to assess how accurately it predicts mobile phone prices.
Finally i got the best score with Random forest regression then i perform cross validation and hyperparameter tuning to check it suerly.
As a final report i have got the Best model for Price prediction is " RANDOM FOREST REGRESSION " and most important featuer are Memory, RAM, battery,and Mobile phone's heights are highly correlated to our Target variable Price. 



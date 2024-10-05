# Mobile_Price_Prediction

In this project, dataset is being used to do Data processing.
All the steps tht are needed - data Preprocessing till Prediction of mobile_Price is done..
1) Data Loading
Here in the CSV file is uploaded with the mobile secification data being stored in it .

2) Data Cleaning and reshaping
After loading the dataset , null values are checked in order to make the dataframe more reliable to use .
NAN's were being filled up with the mean value of the atrribute --> resulting in better accurate numbers.
Dataset shape and datatypes also checked.
Conversion of object data type to datye-time is also done for the date variable.

3) Data Enrichment by Visualization
After clean the data , I ued the Seaborn library to visualize the data.
Boxplot has been used to get the view of the data --> some outliers were being used.
After removing the outliers , Correlation [corr()] is also used .
For correlation , I used the heat map that clearly showed that durin clear sky , there were more rides.
The above gave an insight that more business can be done in the spring season by introducing more offers.

4) Handling Outliers
The outliers that were noticed are handled by using the Z score method .
Instead of removing the outliers , those are being caped with their accurate values --> resulting in better insights.

5) Numerical Features and  Split
Now to predict the data , we had to align everything in the numerical data type as it is not the classification problem.
After this the data is being split between the X and y varialble.
   X- independent variable , y -dependent variable(to be predicted)
After this the shape and standardiztion is done to have clean picture .

6) Models
   Linear regression - Data is being predicted by using the regression model but didn't show much progress.
   Random Forest - This gave pretty fine behaviour , so continued with this.
   XGboost - Tried boosting as well to have better accuracy . Took a random exampple and did prediction ---> It was fairly close.

7) Feature Analysis - It is done by gathering all the features and taking top 5 to evaluate the business insights. 

 

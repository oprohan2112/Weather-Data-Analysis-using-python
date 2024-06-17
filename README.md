# Weather-Data-Analysis-using-python
Here , A Weather dataset is a time series dataset with per hour information weather condition at particular location . it records temperature , dew point temperature , Relative Humidity , Wind Speed , Visibility ,Pressure And Conditions .  This data is avalible as a csv file . we are going to analyse this dataset using the pandas dataframe .

Tool used :- Jupyter , python pandas library. 

The commands that we used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.

--------------------------------------------
QUESTIONS I WANT TO ANSWER FROM DATASET ARE : -

-- Q. 1)  Find all the unique 'Wind Speed' values in the data.

-- Q. 2) Find the number of times when the 'Weather is exactly Clear'.

-- Q. 3) Find the number of times when the 'Wind Speed was exactly 4 km/h'.

-- Q. 4) Find out all the Null Values in the data.

-- Q. 5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'.

-- Q. 6) What is the mean 'Visibility' ?

-- Q. 7) What is the Standard Deviation of 'Pressure'  in this data?

-- Q. 8) What is the Variance of 'Relative Humidity' in this data ?

-- Q. 9) Find all instances when 'Snow' was recorded.

-- Q. 10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.

-- Q. 11) What is the Minimum & Maximum value of each column against each 'Weather Condition ?

-- Q. 12) Show all the Records where Weather Condition is Fog.

-- Q. 13) Find all instances when 'Weather is Clear' or 'Visibility is above 40'.

-- Q. 14) Find all instances when :
   A. 'Weather is Clear' and 'Relative Humidity is greater than 50'
   or
   B. 'Visibility is above 40'

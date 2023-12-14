# Data-Cleaning-Analysis-with-python

In my first python project,i performed an extensive data cleaning and analysis on a NIG_DATA dataset using jupyter notebook, i started by importing the *NUMPY* and *PANDAS* library so as to use the functions attached to them,then i imported the dataset using the .read_csv function and assigned it to a variable.
![](py1.png)

* #### Data Assessment

i started my assessment by firstly checking the number of rows and columns the dataset has, i was able to achieve this by using the ".shape" function, then i checked the column headers using the ".column" function. i also checked for the datatypes of each column using the ".dtypes" function.

![](py2.png)
 I continued my assessment by subsetting the columns and checking for inconsistencies and null values(nan). then i checked *AGE* column, checked for the minimum and maximum value and also checked for outliers, These are the assessment i made.

 ![](py3.png)

 ![](py4.png)

 ![](py5.png)

 ![](py6.png)

 ![](py7.png)

 ![](py8.png)

 ![](py9.png)

 after assessing the dataset,i discovered and listed the problems and irregularites within the dataset, so as as to know how to perform the data cleaning.

 
* #### Data Cleaning

  I started the cleaning by assigning the proper datatype to the columns that had datatype issues, and assigning them to the columns. i started with the *GENDER* column

  ![](py10.png)

  I took a copy of the datatset by i started my cleaning. I also cleaned the column headers by
  
  1. Adding Space between combined values

  2. Converting all caps to capital initials

  3. Replacing . and As attached with others.

  ![](py11.png)

  in the *AGE* column, i replaced the outliers with the median,then converted it from float to integers. so these are all the cleaning i performed on the columns.

  ![](py12.png)

  ![](py13.png)

  ![](py14.png)

  ![](py15.png)

  ![](py16.png)

  ![](py17.png)

  ![](py18.png)

  ![](py19.png)

  ![](py20.png)

  ![](py21.png)

  ![](py22.png)

  ![](py23.png)

 * #### Exploratory Data Analysis
   i performed an EDA by creating a histogram plot on the *AGE*  column to show the age distribution of the ages. i also created a bar chat on the *SUBJECT_CAR_MAKE* column with the value count while sorting in ascending order.

   ![](py24.png)

   ![](py25.png)

 * #### Univariate Analysis

   i imported *matplotlib.pyplot as plt* to perform univariate analysis and create more plots analyzing a single variable.

   ![](py26.png)

   ![](py27.png)

   ![](py28.png)

   ![](py29.png)

   ![](py30.png)


 * #### Bivariate Analysis

   I imported *SEABORN* library to conduct bivariate categorical analysis,to create special plots and to understand the relationship between *AGE* and *no_po* column.
   ![](py31.png)

   ![](py32.png)

   ![](py33.png).

   

   

   

  

  

  

  

  

  

  

  

  
  

 

 

 
 

 


# Netflix-EDA
# Exploratory Data Analysis Performed on Netflix Dataset 
## dataset was explored to answer following questions 
1. which type of content is nore present on Netflix TV-Shows or Movies, 
2. Distribution of Content Month wise and Year Wise
3. What is Average run duration for TV-Shows and Movies 
4. Which genre has maximum content on Netflix
5. Content Distribution based on Ratings
6. Content Distribution Based on Rating country wise

## Steps Involved while performing EDA
1. Reading Dataset(after reading it we got to know that there are multiple columns which has nested values, multiple columns which has missing values and few columns with wrong ddata type)
2. Unnesting of columns using str.split() then stacking them and finally converting them to a dataframe 
3. Handling missing values and wrong values(eg - rating columns had few values as 70 min which is wrong so removing min from it then for missing values we replaced them with mode values)
## Programming language and tool Used
1. Python Programing Language and Python EDA and Data visualization libraries 
2. MS-Excel 
3. Jupyter Notebook

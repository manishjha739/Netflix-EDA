# Netflix-EDA
Exploratory Data Analysis Performed on Netflix Dataset 
dataset was explored to answer following questions 
Q1. which type of content is nore present on Netflix TV-Shows or Movies, 
 Q2. Distribution of Content Month wise and Year Wise, 
  Q3. What is Average run duration for TV-Shows and Movies 
Q4. Which genre has maximum content on Netflix,
 Q5 Content Distribution based on Ratings,
  Q6 Content Distribution Based on Rating country wise

Steps Involved while performing EDA
1. Reading Dataset(after reading it we got to know that there are multiple columns which has nested values, multiple columns which has missing values and few columns with wrong ddata type)
2. Unnesting of columns using str.split() then stacking them and finally converting them to a dataframe 
3. Handling missing values and wrong values(eg - rating columns had few values as 70 min which is wrong so removing min from it then for missing values we replaced them with mode values)

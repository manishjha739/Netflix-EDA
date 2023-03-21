# About NETFLIX
Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

# Business Problem
Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries

# Dataset info
Show_id: Unique ID for every Movie / Tv Show
Type: Identifier - A Movie or TV Show
Title: Title of the Movie / Tv Show
Director: Director of the Movie
Cast: Actors involved in the movie/show
Country: Country where the movie/show was produced
Date_added: Date it was added on Netflix
Release_year: Actual Release year of the movie/show
Rating: TV Rating of the movie/show
Duration: Total Duration - in minutes or number of seasons
Listed_in: Genre
Description: The summary description

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

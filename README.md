# Netflix Content Analysis

## Table Of Content
- [Project Overview](#Project-Overview)
- [Data Sources](#Data-Sources)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- 
### Project Overview
Netflix is a streaming service that offers TV shows, movies, documentaries and more on thousands of devices.
This data analysis project aims to provide insights into the content available on Netflix, focusing on aspects like the types of content (movies vs. TV shows), geographical distribution, release trends, ratings, and notable actors. The analysis will help in understanding patterns and trends in Netflix's catalog.

### Data Sources

Netflix Data: The dataset contains information on movies and TV shows available on Netflix, including details like title, director,	cast,	country, release date, release year, rating, duration, genre and description. 

### Tools

-Python: For data analysis, using libraries like Pandas, NumPy, and Matplotlib/Seaborn for visualization.

-Jupyter Notebook: For running Python scripts and displaying results.

### Data Cleaning/Preparation
- Removing duplicates (only 2 duplicated values were there).
- Handling missing values (Director, Cast, Country, Release_Date, Rating columns had the missing values).    

### Exploratory Data Analysis

EDA involved exploring the Netflix data to answer key questions, such as:

- How many movies & TV shows are in the dataset?
- Show all the movies that were released in year 2000.
- Show only the titles of all TV shows that were released in India only.
- Show all the records, where category is movie and type is comedies or country is United Kingdom.
- For 'House of Cards', what is the show ID and who is the director of this show?
  
  `data[data['Title'].str.contains('House of Cards')]`
  
- In which year highest number of the TV shows and movies were released?
- In how many movies/shows Tom Cruise was cast?
- What are the different ratings defined by Netflix?
   -How many movies got the 'TV-14' rating in Canada?
   -How many TV show got the 'R' rating after year 2018?
- What is the maximum duration of a movie/show on Netflix?


### Results/Findings
Trends in Content Release: Most releases occurred in recent years from 2017 to 2020, 2019 had most releases.
Top-rat
Notable Cast Insights: Certain actors appear more frequently, indicating partnerships or popularity on the platform.

### Limitations

- Some fields, such as 'Director' and 'Cast' have significant number of missing values.
- The dataset only includes content information up to the year 2020, which may not reflect recent trends or changes in Netflix's catalog.

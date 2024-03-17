# Netflix-Movies-and-TV-Shows

Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

**The dataset was analyzed in terms of:**
1. **How many movies and TV shows have been published on the Netflix platform?**
2. **Movies and TV shows with the most published directors?**
3. **From which countries are the most movies published?**
4. **Which production years have the most movies on the Netflix platform?**
5. **In which age group are the most movies and TV shows published?**
6. **What is the most common duration of movies published on the Netflix platform?**
7. **How many seasons do TV shows most frequently have?**
8. **Which category has the most movies on Netflix?**
9. **Which category has the most TV shows on Netflix?**

## Dataset
The database was downloaded from the [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) website.

The database contains information about:
* show_id
* type
* title
* director
* cast
* country
* date_added
* release_year
* rating
* duration
* listed_in
* description

The database has 8807 rows and 12 columns.

## Data Cleaning
After loading the dataset, its structure, encoding, missing values, and duplicates were checked. 

According to the applied function, our data doesn't contain any duplicates but includes missing values NaN. Since 3475 rows had missing values, they were removed, resulting in a database with 5332 rows.

The data encoding was checked, and the date format in the "date_added" column was converted accordingly.

After cleaning the data, the indexes were reset.

## Analysis and visualization of data

# Investigating Netflix Movies 🎬📊  

Explore Netflix’s 1990s movie catalog through exploratory data analysis (EDA).  
This project focuses on understanding movie durations and short action films from the decade, combining Python and pandas to extract insights.  

---

## Guiding Questions  
1. What was the most frequent movie duration in the 1990s?  
2. How many short action movies (less than 90 minutes) were released in the 1990s?  

---

## The Data  

**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.  

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex your exploratory data analysis skills and dive into the entertainment industry.  

You work for a production company that specializes in nostalgic styles. You want to do some research on movies released in the 1990s. You'll delve into Netflix data and perform exploratory data analysis to better understand this awesome movie decade!  

Dataset provided: **`netflix_data.csv`**  

| Column         | Description                  |  
|----------------|------------------------------|  
| `show_id`      | The ID of the show          |  
| `type`         | Type of show                |  
| `title`        | Title of the show           |  
| `director`     | Director of the show        |  
| `cast`         | Cast of the show            |  
| `country`      | Country of origin           |  
| `date_added`   | Date added to Netflix       |  
| `release_year` | Year of Netflix release     |  
| `duration`     | Duration of the show        |  
| `description`  | Description of the show     |  
| `genre`        | Show genre                  |  

---

## How I Approached the Project  

1. **Filtered the data** for movies released in the 1990s by subsetting the DataFrame and selecting rows with release years between 1990 and 1999.  
2. **Found the most frequent movie duration** by visualizing the distribution of durations for movies in the 1990s.  
3. **Counted the number of short action movies (< 90 min)** by subsetting for “Action” movies and applying a conditional count on duration.  

---

## Key Deliverables  

- Filtered and subsetted Netflix movie data for the 1990s.  
- Identified the most common movie duration during that decade.  
- Counted the number of short action movies released in the 1990s.  
- Practiced EDA workflows using pandas and Python.  

---

## Skills Used  

- Python (pandas, matplotlib)  
- Data cleaning & filtering  
- Exploratory data analysis (EDA)  
- Data visualization  
- Conditional logic in pandas  

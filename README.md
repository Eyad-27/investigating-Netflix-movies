# Investigating Netflix Movies 🎬

Explore Netflix’s 1990s movie catalog through exploratory data analysis (EDA).  
The project focuses on identifying the most frequent movie duration and counting short action movies released in that decade.  

---

## Guiding Questions
- What was the most frequent movie duration in the 1990s?  
- How many short action movies (<90 minutes) were released in the 1990s?  

---

## The Data
### **netflix_data.csv**
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

---

## How I Approached the Project
1. Subsetted the dataset to include only movies from the 1990s.  
2. Visualized movie duration distributions to find the most frequent value.  
3. Filtered for short action movies and counted how many were released.  

---

## Key Deliverables
- Filtered 1990s movies using **pandas DataFrames** and Boolean logic.  
- Conducted **EDA** to determine the most common movie duration.  
- Applied **data cleaning and subsetting** to focus on genres and durations.  
- Strengthened skills in **matplotlib visualization** to summarize insights.  

---

## Skills Used
- **Python**: pandas, matplotlib  
- **Techniques**: Data cleaning, filtering, subsetting, visualization, EDA  

# Netflix Data Analysis (Python)

This project performs a comprehensive exploratory analysis of Netflix’s content dataset using Python. The goal is to uncover patterns in genre distribution, content growth over time, country contributions, and other insights that reveal how Netflix’s catalog has evolved.

## Project Overview

The dataset contains information about movies and TV shows available on Netflix across different years, along with metadata such as genres, country of origin, type (Movie/TV Show), and release dates. This analysis uses Python libraries (pandas, numpy, matplotlib, seaborn) to clean the data, explore trends, and generate visual insights.

## About the Dataset

- **File(s):** e.g. `Netflix_Data.csv`
- **Rows / Entries:** Tens of thousands (depending on source)  
- **Columns / Features Include:**
  - `show_id` (unique identifier)  
  - `type` (Movie or TV Show)  
  - `title`  
  - `director`  
  - `cast`  
  - `country`  
  - `date_added`  
  - `release_year`  
  - `rating`  
  - `duration`  
  - `listed_in` (genres / categories)  
  - `description`  
- **Purpose:** To analyze how Netflix’s content library is distributed across genres, regions, and time, and to infer growth and strategic direction.

## Tasks Performed in the Notebook

- Loaded the dataset and previewed basic structure  
- Handled missing or null values, normalized columns (e.g. splitting multi-valued fields)  
- Parsed `date_added` and `release_year` fields to derive year, month features  
- Cleaned and standardized country / genre lists (splitting multi-country or multi-genre entries)  
- Aggregated counts by year, type (Movie / TV Show), and genre  
- Explored country-wise contributions over time  
- Analyzed evolution of Netflix’s catalog: how many titles added each year, by type  
- Examined co-occurrence of genres across the catalog  
- Created visualizations (bar charts, line plots, heatmaps, stacked charts) to illustrate:
  - Growth in number of titles over time  
  - Genre trends (which genres increase or decline)  
  - Top contributing countries  
  - Distribution of movie vs TV shows  
  - Genre correlation / overlaps  

## Key Findings

- Over time, Netflix’s catalog has expanded steadily, with significant growth in **TV Shows** compared to **Movies**.  
- Certain genres (e.g. Drama, Documentary, Comedy) consistently appear among the most common, while niche genres have smaller representation.  
- Some countries (notably the U.S. and India) contribute disproportionately to Netflix’s catalog, especially in recent years.  
- The diversity of genres per title has increased (many titles now list multiple genres), showing blending of categories.  
- Genre combinations (e.g. Drama + Romance, Documentary + Biography) are common, indicating cross-genre content.  
- The rate of new additions fluctuated year to year, but there is an upward trend in content volume.

## Interesting Insight

An interesting pattern is that Netflix seems to favor investing more in **TV Shows** over movies in recent years. This may tie into long-term subscriber engagement strategies — longer-form content keeps viewers more engaged over time. Also, emerging countries in the dataset (e.g. India) are contributing increasingly, potentially pointing to regional content localization strategies.

## Conclusion

This analysis sheds light on how Netflix’s content library has evolved in terms of volume, genre mix, and geographical contribution. Through systematic cleaning, aggregation, and visualization of data, the project surfaces meaningful patterns in how Netflix is shaping its catalog strategy. The insights may be useful for content strategists, market analysts, or anyone seeking to understand media streaming trends.

## Author 
**Devansh Singh Tomar**


## Requirements

- **Python 3.12.0**
- **Jupyter Notebook**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**


## How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/bersercz/Netflix_Analysis_py.git
   cd Netflix_Analysis_py

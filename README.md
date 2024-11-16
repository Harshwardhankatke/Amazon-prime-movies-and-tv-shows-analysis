Amazon Prime Movies and TV Shows Analysis Dashboard (Power BI)
Objective
The purpose of this project is to create an insightful, interactive, and visually appealing Power BI dashboard to analyze and present key performance metrics and trends related to movies and TV shows on Amazon Prime. This project aims to provide data-driven insights into content trends, customer preferences, and the distribution of genres and ratings.

Key Analysis Conducted (Questions Answered)
Total Number of Movies and TV Shows: Displayed the count of movies and TV shows available on Amazon Prime.
Year-wise Content Addition: Analyzed trends in the addition of content over the years.
Most Popular Genres: Identified the most common genres for movies and TV shows.
Top-Rated Movies and TV Shows: Determined the highest-rated content.
Distribution by Content Rating: Showed the classification of content by rating (e.g., PG, PG-13, R).
Country-wise Content Analysis: Highlighted the countries producing the most content available on Amazon Prime.
Content Length Analysis: Analyzed the duration or runtime distribution for both movies and TV shows.
Content Language Distribution: Showed the availability of content in various languages.
Recent Trends: Identified which types of content (movies or TV shows) have increased in popularity over recent years.
Data Cleaning Process
Removed Duplicate Entries: Ensured there were no duplicate records in the dataset.
Standardized Naming Conventions: Uniformly formatted movie and TV show titles and genres.
Filled Missing Data: Used imputation techniques to fill missing data in important columns like release year and rating.
Dropped Irrelevant Columns: Removed columns that were not relevant to the analysis, such as unique identifiers not useful for aggregation or visualization.
Filtered Invalid Data: Excluded entries with incomplete or inconsistent data.
Data Modeling
Created Relationships: Linked relevant data tables using unique identifiers such as content ID.
Date Table: Built a dedicated Date table for accurate time-based analysis and connected it with the release year of content.
Measure Table: Created a measure table for key metrics such as total content count, average rating, and year-over-year growth.
Calculated Columns and Measures: Developed calculated columns for content type (movie vs. TV show) and DAX measures to capture KPIs like total movies, total TV shows, and year-on-year growth.
Visualizations and Features
KPIs (Cards): Displayed total movies, total TV shows, and average content rating.
Year-wise Content Additions (Line Chart): Illustrated the growth in the number of movies and TV shows over time.
Top Genres (Bar Chart): Highlighted the most popular genres.
Content by Country (Map Visualization): Showed a geographical distribution of content.
Rating Distribution (Donut Chart): Visualized the spread of content across different ratings.
Top-Rated Content (Table): Listed movies and TV shows with the highest ratings for quick insights.
Language Distribution (Bar Chart): Showed the availability of content in various languages.
Interactive Filters (Slicers): Provided filters to slice data by:
Content type (Movies, TV Shows)
Genre
Country of origin
Release year
Language
Content rating
Sample Dashboard Screenshots
Include sample images or screenshots here to give viewers a preview of your Power BI dashboard.

Key Insights
Content Growth: The number of movies and TV shows on Amazon Prime has shown a significant increase, particularly in the last decade.
Popular Genres: Drama, Comedy, and Documentary are the most common genres.
High Ratings: A significant proportion of highly-rated content is found in specific genres such as Documentaries and Dramas.
Country Contributions: The United States contributes the most content to Amazon Prime's library, followed by other countries like the UK and India.
Diverse Languages: The platform hosts a range of content in various languages, with English being the most dominant.
Conclusion
The Amazon Prime Movies and TV Shows Analysis Dashboard provides a comprehensive overview of the platform's content trends, including growth patterns, popular genres, and ratings distribution. This analysis can guide stakeholders in understanding content strategies and identifying areas for improvement in catalog diversity and viewer satisfaction.

Future Enhancements
Customer Demographic Analysis: Incorporate data on viewer demographics for deeper insights into content preferences.
Comparison with Other Streaming Services: Extend the analysis to include comparisons with competitors like Netflix and Hulu.
Sentiment Analysis: Implement sentiment analysis on viewer reviews for qualitative insights.
How to Run the Project
Data Source: The dataset used can be found [link to dataset if available].
Software Required: Microsoft Power BI Desktop.
Steps:
Open the Power BI file (.pbix) in Power BI Desktop.
Refresh the data and ensure the connections to any data sources are correct.
Interact with the dashboard by applying filters and exploring the visualizations.
License
This project is licensed under the MIT License – see the LICENSE file for details.

Acknowledgments
Data Source: [Mention the data provider or source]
Inspiration: Aimed to provide useful insights for content strategists and platform managers.

# Movie_-_TV_Show_Metadata_Analysis
This project explores patterns in movie and TV show metadata, analyzing genre trends, director influence, certificate impact, and more.
# Tools
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- PostgreSQL
- Excel
- Power BI
  
 Excel Dashboard for movie and Tv Metadata analysiswith Genre and Ratings (2023)

<img width="1172" alt="IMBD_genre_rating_Dashboard" src="https://github.com/user-attachments/assets/dcbcb6f1-6ce1-4c82-a983-549e217af01e" />

Power BI Dashboard for Movie and Tv Metadata analysis with Genres and Ratings (2023)


<img width="905" alt="IMBD_Dashboar_metadata" src="https://github.com/user-attachments/assets/c7cd16b0-048d-4c07-a01b-cdc3bba34d76" />


Python project for Movie and Tv Metadata analysis with Genres and Ratings (2023)

Project Overview:

This project focuses on analyzing an IMDb-style dataset of movies and TV shows using Python. The goal is to clean the data, explore relationships between features (like rating, genre, runtime, and votes), and extract meaningful insights through visualizations and summaries.

Dataset Columns:

movie, genre, certificate, rating, runtime, stars, description, votes, director.

Data Cleaning:

1. Removed duplicates
2. Converted columns (e.g., runtime from "120 min" → 120)
3. Handled missing values
4. Cleaned votes (removed commas, converted to int)


<img width="1114" alt="Screenshot 2025-05-23 at 11 39 08 PM" src="https://github.com/user-attachments/assets/83a3ce3d-b3b0-438b-81a8-ece8f90d61ea" />

Try Some more cleaning it's help me more precise analysis

<img width="1111" alt="Screenshot 2025-05-23 at 11 47 03 PM" src="https://github.com/user-attachments/assets/2f0477e1-4b36-4467-af47-76bc9f9d5dbf" />

some Statistical Analysis
<img width="953" alt="Screenshot 2025-05-23 at 11 53 41 PM" src="https://github.com/user-attachments/assets/452706d8-b375-4f00-9980-1c3ac4d21ad3" />

Exploratory Data Analysis (EDA) and Visualizations:

1. Distribution of Movie Ratings

<img width="742" alt="Screenshot 2025-05-23 at 11 57 49 PM" src="https://github.com/user-attachments/assets/d4570ac6-ce32-4cef-81a8-a472f38d6ade" />

Insight:
Most movie ratings seem to be clustered around the 6–8 range, suggesting that movies generally get average to good reviews.

2. Movies with Highest Votes

<img width="838" alt="Screenshot 2025-05-24 at 12 03 38 AM" src="https://github.com/user-attachments/assets/5f844b1b-4e4d-4106-936d-5d69c69db24a" />

Insight:

i. Movies with the most votes are usually the most popular and watched by a lot of people.

ii. A high number of votes can also mean that fans are very active or the movie was well-promoted.

iii. These top-voted movies are often part of big movie series (franchises), showing that they have a large number of fans.

3. Plot the genre breakdown

<img width="1027" alt="Screenshot 2025-05-24 at 12 08 21 AM" src="https://github.com/user-attachments/assets/68cde5aa-eec6-4207-8eab-346ce4180f21" />

4. Rating by Certificate

<img width="964" alt="Screenshot 2025-05-24 at 12 11 37 AM" src="https://github.com/user-attachments/assets/2f24f8c0-ebb6-4714-95fa-6d4223eaac35" />

5. Movies by Certification and Average Rating

<img width="1035" alt="Screenshot 2025-05-24 at 12 13 45 AM" src="https://github.com/user-attachments/assets/119f4ab4-6f74-41e2-b407-4492e807c584" />

Insight:

i. Movies with certificates like 16+ often have higher ratings, which means adult or mature content might get better reviews.

ii. On the other hand, family-friendly movies may have lower ratings, possibly because they are made for a wider audience, not just serious movie fans.

6. Top Directors by Average Rating

<img width="1012" alt="Screenshot 2025-05-24 at 12 17 19 AM" src="https://github.com/user-attachments/assets/b1744ba0-9100-4634-a5a8-d01d412ceaea" />

7. Trend of Popular Directors by Ratings

<img width="991" alt="Screenshot 2025-05-24 at 12 19 08 AM" src="https://github.com/user-attachments/assets/4483a6fd-3e01-4511-97e1-ae4f3e567e1d" />

 Insight:

 i. Directors with higher average ratings might indicate consistent quality in their works.

 ii. If certain directors frequently receive higher ratings, it may indicate a loyal following or unique filmmaking style.
 
8. Which Stars Appear Most Often?

<img width="1031" alt="Screenshot 2025-05-24 at 12 23 08 AM" src="https://github.com/user-attachments/assets/f62c061a-f159-453d-bee0-87f5096763d3" />

 Insight:

 i. Some stars appear in many different movies or shows. These actors may be very popular or in high demand.

 ii. Seeing the same names often could mean they are part of successful series or are trusted by directors for important roles.

 iii. This also shows which stars are most active in the industry.

9. Votes vs Rating – Are popular movies always better?


<img width="1009" alt="Screenshot 2025-05-24 at 12 26 17 AM" src="https://github.com/user-attachments/assets/c4c042b3-9ac9-46b0-bec2-ffdc0ab56971" />

 Insight:

 i. Highly voted movies tend to cluster around popular ratings (7–8).

 ii. Some low-vote movies still have very high ratings (potential hidden gems or bias).

10. Average Rating by Genre


<img width="950" alt="Screenshot 2025-05-24 at 12 29 40 AM" src="https://github.com/user-attachments/assets/23f844b7-77ff-422b-bc69-56886168afbc" />

 Insight:

 i.Some genres (e.g., Animation, Documentary, etc.) might have higher average ratings than others.

 ii.This means people may like these genres more, showing their personal taste or preference.

 iii.If a genre always gets high ratings, it could also mean that movies in that genre are made with better quality.

11. Top 10 Most Popular Genres

<img width="1022" alt="Screenshot 2025-05-24 at 12 32 21 AM" src="https://github.com/user-attachments/assets/f20451c3-f721-46dc-9d0b-89b55b3d715d" />

 Insight:

i. Action, Adventure, and Drama are the most common genres, which might suggest that these are the genres with a broad audience.

ii. The prevalence of these genres can help direct decisions about what types of shows or movies to recommend or create.

iii. A diversity of genres appearing frequently could suggest an increasing trend for varied content.

12. Correlation Matrix of Numeric Variables

<img width="819" alt="Screenshot 2025-05-24 at 12 32 39 AM" src="https://github.com/user-attachments/assets/a9d00ffb-b44a-4bac-8ee5-b297eaa04b93" />

 Insight:

 i.If ratings and votes have a strong positive connection, it means that movies with more votes usually get higher ratings. 
   So, popular movies (watched by many people) are often liked more.

 ii.If runtime and rating do not have a connection, it means the length of a movie doesn’t really affect how much people like it.







 



   











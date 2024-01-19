# Spotify_Data_Analysis

MOTIVATION

The motivation behind this project lies in the desire to gain comprehensive insights into my music streaming habits and preferences between the dates 05.12.2022 and 05.12.2023 on Spotify app. By analyzing the extensive dataset capturing my listening history, the goal is to uncover patterns, trends, and notable statistics related to the artists and songs that dominate my streaming experience. This project aims to provide a detailed exploration of my musical journey, identifying favorite tracks, preferred time slots for streaming and much more. This exploration is not only a personal quest to rediscover favorite tracks and moments but also an opportunity to enhance my data analysis skills and utilize various visualization techniques. Through this project, I hope to gain valuable insights into how my music preferences evolve, the impact of seasons or times of the day on my listening habits, and any other intriguing aspects that may emerge from the data.



DATA SOURCE

The data for this project was gathered from my personal Spotify account and provided by Spotify in JSON format. This comprehensive dataset contains specific information about each music played, such as track name, artist, duration, and timestamps. To begin the project, I turned the JSON data into a structured format in Python, primarily utilizing libraries like pandas, seaborn, and matplotlib for analysis and visualization.



DATA ANALYSIS

This project's data analysis included several key techniques and stages to derive meaningful insights from my Spotify streaming history. Initially, I loaded the data into a pandas DataFrame and investigated its structure and content. Following that, I performed data cleaning by handling missing values and converting timestamps. The analysis proceeded with the creation of various visualizations using seaborn and matplotlib libraries, such as histograms depicting song play counts, distribution of playtimes, and counts by season. Additionally, I used seaborn's countplot to visualize streaming trends by different time dimensions, including day of the week and season. The project used a variety of analytical and visualization techniques to extract insights from my music streaming data.



FINDINGS

Between the dates 05.12.2022 and 05.12.2023 I have streamed 12872 songs.

There are 250 songs that have been streamed more than 10 times.

There are more than 1400 songs that have been streamed only once.

Number of songs played is higher on Thursdays compared to other days of the week.

My most active time is between 7PM - 8PM.

%75.43 of the songs streamed is on weekdays.





LIMITATION AND FUTURE WORK

While this project has provided valuable insights into user streaming patterns and preferences, the absence of genre information for the songs in the dataset restricts a more in-depth analysis of user preferences based on music genres. For the future, next year’s stream data could be analyzed, and these two years can be compared to each other. This would, unveil evolving trends, shifts in user preferences, and changes in popular artists over time. Furthermore, introducing machine learning models to the project could enable predictive analysis, allowing for the forecasting of future streaming trends or predicting user engagement based on historical data.


# Exploratory-Data-Analysis-on-Spotify-2023-Dataset---Concepcion-Ry
This repository contains the Exploratory Data Analysis (EDA) of the Spotify dataset, which aims to explore the data's features and relationships to gain insights into the tracks.
## Table of Contents
* Objective
* Introduction
* Included Materials
* Dependencies
* Executing Program
* Conclusion
* Recommendation
* Authors
* Version History
* Acknowledgement
## Objectives
- Explore and analyze the Spotify dataset to understand the factors influencing track popularity.
- Identify trends, patterns, and correlations between musical attributes (e.g., tempo, energy, danceability) and key metrics like streams and release dates.
- Use visualizations (e.g., bar charts, histograms, scatter plots) to uncover insights and make the data easily interpretable.
- Investigate relationships between streams and other variables to draw meaningful conclusions.
## Introduction
Exploratory Data Analysis (EDA) of Spotify's Most Streamed Songs examines the characteristics and relationships within the dataset to uncover insights about the most streamed songs. The dataset contains 953 entries and 24 columns, which include song attributes, artist details, and streaming metrics.
## Included Materials
- **Spotify Dataset.ipynb** - ipynb file containing the data analysis
- **spotify-2023.csv** - excel file containing the dataset of spotify tracks
- **README.md** - project documentation
## Dependencies
* **Pandas**: Data manipulation and analysis
* **Numpy**: Numerical operations
* **Matplotlib**: Plotting graphs and visualizations
* **Seaborn**: Statistical data visualization
* **Random**: Generating random numbers and performing random sampling
* **Warnings**: To handle warnings during execution
* **Plotlly.express**: For interactive visualizations
* **Plotly.io**: For rendering interactive plots created with Plotly.
## Executing Program
### 1. Importing Libraries Needed
  In the initial step, essential libraries for data manipulation, numerical operations, and visualization are imported. pandas is used for data manipulation, providing powerful tools for handling and analyzing structured data in tables. numpy is imported to handle numerical operations and arrays, allowing for efficient mathematical computations. matplotlib.pyplot is used for generating static visualizations, while seaborn is imported for creating more advanced and aesthetically pleasing statistical plots. random allows for generating random numbers and performing random sampling, which is useful for data shuffling or creating random test data. Finally, warnings is used to control warning messages, and the filterwarnings('ignore') function is applied to suppress unnecessary warnings during execution.
### 2. Comprehension and Preparation of Data
  In this part of the data analysis, we try to understand and conduct an initial exploration in the data. The dataset includes columns like track_name, artist(s)_name, released_year, streams, and various musical attributes such as danceability, energy, and bpm. It contains both numerical data (e.g., streams, bpm) and categorical data (e.g., key, mode), with categorical columns converted to the 'category' type for more efficient handling. Missing values were found in the key and in_shazam_charts columns, which were addressed by filling them with the mode of their respective columns. Outliers in the numerical columns were detected and managed using boxplots, resulting in a cleaner dataset for analysis. 
### 3. Summary of Statistics
  Statistical measures for numerical columns were obtained using the describe() function, offering insights into the average number of streams, bpm distribution, and the range of danceability. Additionally, unique value counts for categorical columns were analyzed, showcasing the variety of artists and song attributes.
### 4. Data Visualization
- Bar Plots
  - **Top 5 Most Streamed Tracks**: Bar plots were used to display the top 5 songs with the highest streams.
  - **Top 5 Most Frequent Artists by Track Count**: Bar plots also revealed the top 5 artists with the most tracks in the dataset.
  - **Total Streams per Year**: A comparison of total streams by year was visualized using bar plots, highlighting the year with the highest number of streams.
  - **Number of Tracks Released per Month**: Bar plots were used to track the number of song releases per month, showing that January had the highest number of releases.
  - **Top 10 Artists in Playlists and Charts**: Analysis of bar plots showed The Weeknd as the most frequently appearing artist in playlists and charts.
  - **Track Comparison Between Spotify and Apple Playlists/Charts**: A bar plot comparison indicated that Spotify favors popular tracks more than Apple playlists/charts.
- Line Chart
  - **Number of Tracks Released per Year**: A line chart was used to identify trends in track releases by year, showing that 2022 had the highest number of tracks released in a single year.
- Heat Map
  - **Correlation Between Streams and Musical Attributes**: A heat map was used to examine the correlation between streams and musical attributes. It was found that danceability has a moderate positive correlation with valence, meaning that more danceable songs tend to have a more positive or happy mood. Additionally, energy also shows a moderate positive correlation with valence, suggesting that higher-energy songs often convey a happier tone.
- Scatter Plot
  - **Correlation Between Danceability and Energy**: A scatter plot was used to explore the relationship between danceability and energy, revealing a weak positive correlation. While higher danceability is often associated with higher energy, significant variation is present.
  - **Correlation Between Valence and Acousticness**: Another scatter plot was used to examine the relationship between valence and acousticness. The results showed no clear linear correlation, indicating that a song's acoustic qualities do not strongly predict its mood or positivity.
- Pie Chart
  - **Mean, Median, and Standard Deviation of 'Streams'**: We have identified the descriptive statistics of the 'streams' column using a pie chart.
  - **Distribution of Songs by Mode**: We were able to distribute the tracks by mode using a pie chart. We have identified that there are more songs in the Major mode than the Minor mode, indicating a slight prevalence of Major mode songs.
  
## Conclusion
The Exploratory Data Analysis (EDA) of the Spotify dataset offered a thorough understanding of the factors impacting song popularity on the platform. Through statistical analysis and visualizations, important trends and relationships were uncovered, providing valuable insights into the music streaming landscape. This analysis lays the groundwork for future modeling and predictive studies to further explore the dynamics of music consumption on streaming platforms.
## Recommendation
1. Data Tyding
   - To ensure accurate analysis, it is crucial to address any missing values in the dataset, as they can lead to biased or incorrect conclusions. Missing data can be handled through imputation or removal, depending on the context. Additionally, the dataset should be organized for clarity, with proper data types assigned to each column. If necessary, convert categorical variables into numerical ones or vice versa. It’s also important to remove outliers and duplicates, as they can distort the analysis. Proper data tidying ensures that the data is clean, consistent, and ready for analysis.
2. Data Visualization
   - To effectively visualize the data and uncover trends, it is important to select the right type of chart or graph that best represents the data. This ensures that the insights are clearly communicated and easily understood. Additionally, double-check that the data displayed in the visualizations matches the raw data, as discrepancies can lead to misinformation and inaccurate conclusions. Proper alignment between the visual and raw data is crucial for maintaining the integrity of the analysis and ensuring that the findings are reliable and meaningful.

## Authors
- Ryan Concepcion
## Version History
- 0.1
  - Initial Release
  - 0.1.2
    - README file edits
    - File uploaded edits
- 0.2
  - final README file edits

## Acknowledgement
- Youtube
- Github
- Chatgpt

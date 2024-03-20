# Big 5 European Leagues Teams Analysis

## Overview
This project aims to analyze and visualize the stats, performances, and comparisons of various football teams from the top 5 leagues across Europe from season 2001-02 onwards. The data is sourced from the Football-Data website. The data has been webscraped using the Beautiful Soup package and exported to a CSV file. Then, the data has been processed using Power BI to create a database for easy management, analysis, and exploration of the data visually and to gain valuable insights.

## Dataset
The dataset used in this project contains historical data of the match fixtures of various teams from the top 5 leagues across Europe from season 2001-02 onwards. The data has been sourced from the website of [Football-Data](https://www.football-data.co.uk/data.php), which ensures its authenticity and reliability. This dataset is a result of a very extensive effort of webscraping and integrating different data links within the source website. The data is uploaded as CSV files on the website and it is segmented seasonwise and leaguewise across the various countries in Europe. I was able to pull every information from these CSV files uploaded on the website. I did found some missing data in couple of CSV files on the website. However, rest of the data is correct on the source website and has been scraped 100% successfully here.

I have only considered the top two divisions for every country's league. The dataset provides a granular view of more than 110,000 games from the biggest 5 European football (soccer) leagues: England, Spain, Germany, Italy, France.

I have only analyzed the data post 2001-02 season; however, I have extracted the entire data from all the seasons, beginning from 1993-94 until the present. The dataset is extracted and analyzed via two separate Python scripts for different time periods, as mentioned below:
- past-data.ipynb - This jupyter notebook contains the code for scraping match data about each game from season 1993-94 till 2022-23 and saved to past-data.csv file.
- new-data.ipynb - This jupyter notebook contains the code for scraping match data about each game from season 2023-24 onwards and gets executed real time as a python script in the Power BI working file. This is done to ensure that the most recent data can be updated as required.

headers.txt contains the textual description of each categorical variable.

The dataset includes information such as season, league name, match date, team name, full time match scores, half time match scores, shots on target, shots, fouls committed, yellow cards and red cards.

## Data Processing
The data obtained from the source website requires some preprocessing to clean and transform it into a suitable format for analysis. Jupyter notebook and Power Query Editor within Power BI has been utilized to clean, filter, and transform the data as necessary. This ensures that the data used for the dashboard is accurate and reliable.

## Technologies Used
Python: Jupyter notebook for data scraping, cleaning, filtering, and exporting.

Power Query Editor: For data cleaning, filtering, and transformation into the database.

Microsoft Power BI: For data analysis and visualization.

## Key Highlights
Based on the analysis of all the matches of the Top 5 European League Teams from the last two decades, I have found really interesting insights.
- At least 65% of the time, almost all the teams ended up having the same result at full time as they were having at half time!
- So clearly, Half Time momentum matters, and teams that are trying to win the league or avoid relegation should focus equally on their half time results as much as they do on their full time results.

## Dashboard Preview
Click the link to access the interactive dashboard - [Big 5 European Leagues Teams Analysis](https://app.powerbi.com/view?r=eyJrIjoiM2ZjOWQwZDctMDkyMi00MDA5LTlhNzUtYTk2ODZlYmZhNWNlIiwidCI6ImRlYTFmNTJjLTI4OWYtNGZiMS05MDU5LTVmMWY3ZjdlNDRjYyJ9)

![Big 5 European Leagues Teams Analysis](/images/football-teams-analysis.png)

## Author
- Prateek Chauhan
- [LinkedIn](https://www.linkedin.com/in/prateekchauhands/)
- [Twitter](https://twitter.com/PrateekC_DS)
- [prateek-chauhan.com](https://prateek-chauhan.com/)

## Contact Me!
Feel free to contact me at [Prateek Chauhan](mailto:prateekchauhan.ds@gmail.com) for any data-related projects, collaborations, questions or suggestions.
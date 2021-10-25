# Movies-ETL
----
### Project Overview
----
Amazing Prime would like to forecast which 'low budget' movies will be most popular, based on several large datasets. If we can determine which movies will be most popular, Amazing Prime will be able to purchase streaming rights early at a lower rate.
In order to prepare for this research, we first required clean datasets with only the pertinent information. 
The below was utilized to retrieve and consolidate this data:
- MovieLens Ratings
- Wikipedia (movie data since 1990)
- Movie dataset via Kaggle

### Process Summary
----
Some pertinent code involved in this analysis is shown in the image below. This block of code is gathering & cleaning data from the datasets mentioned above, and transferring into a Pandas Data Frame.
![This is an image](https://github.com/KEGANCP/Movies-ETL/blob/main/RESOURCES/read_data.png)

Below is an example of the 'movies' data frame after scrubbed to show column headers pertinent for this analysis.
![This is an image](https://github.com/KEGANCP/Movies-ETL/blob/main/RESOURCES/movies_table.png)

After creating a SQL database, we are now prepared to begin Amazing Prime's request for a 'Hack-A-Thon' for individuals to analyize and work toward finding the requested information.

# Spotify

This project an examination of songs in spotify playlist from 1930 to 2023 using SQL and Python(Pandas, Seaborn). Using different SQL querries I look at the different Tracknames and their released year. The correlation or impact of energy, bpm or the speech and acousticness have on the danceability of a song or it being top of the chart in a spotify playlist. 

# Libraries

Pandas 

Sqlalchemy 

Matplotlib.pyplot

Seaborn 
# Methodology
The methodlogy followed for this dataset was to first clean the data and do some transformations using pandas, then connect it to a SQLdatabase from there I use SQL Querries to extract data and do perform analysis. In additon, using Matplotlib and Seaborn I made some visualizations. 

# Results 

![](image/Top_10_Songs_Artists_Streamed.jpg)

The bar graphs above illustrate the most streamed artists and songs over the past years including current year and despite being released in 2017 Ed Sheeran song Shape of is the most streamed. 

![](image/Danceability.jpg)

Looking at the following two scatterplots we look at the correlation between energy and the danceability of a song and also bpm and a danceality of songs. The first graph display a negative correlation between danceability and bpm however, a positive correlation between danceability and energy 

![](image/trendsoy.jpg)

The lineplot show the trends in danceability over the years and it has been ups and downs over different years. 


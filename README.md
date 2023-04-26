# MIST4610 Group Project 2
## Team Name and Members
We are team 21482_4. <br>

### Team Members <br>
* [Jimmy Chancellor](https://github.com/JChancello/) <br>
* [Austin Crispo](https://github.com/austincrispo/MIST-4610-Project-2) <br>
* [Clayton Hoarell](https://github.com/claytonh153454/) <br>
* [Tabea Lent](https://github.com/tabealent/group-project-2) <br>
* [Mary Grace Tippett](https://github.com/mgtipp/MIST4610_project2)

## Dataset Description and Contents
The chosen dataset contains information on the 100 most popular songs worldwide on Spotify by year from 1921-2020. The data was sourced from Spotify Web API and posted to the website [kaggle](https://www.kaggle.com/datasets/ektanegi/spotifydata-19212020). The dataset contains one csv file called data.csv and is comprised of 169909 rows and 19 columns. 
<br><br>
9 columns are of decimal type, 6 are of integer type, and 4 are of type String. The primary key identifies a given track with the ID of the track generated by Spotify. Acousticness, danceability, energy, instrumentalness, valence, liveness, and speechiness range from 0 to 1 describing the named characteristics of the track. Duration_ms is an integer column that ranges from 200k to 300k. Popularity ranges from 0 to 100, tempo ranges from 50 to 150, loudness ranges from -60 to 0, and year ranges from 1921 to 2020. Two attributes, mode and explicit, have a value of either 0 or 1 to specify whether the track is in a minor/major key and explicit/not explicit. The key attribute ranges from 0-11 starting on C as 0, C# as 1, and so on. Another attribute lists the name(s) of the artists, release_date names the date of release in yyyy-mm-dd format, and the name attribute lists the name of the song. Using this data, we can analyze certain questions.

## Generated Questions
1. How has music popularity changed from 1921 to 2020, and what is the relationship between music popularity and track loudness throughout the years? <br>
This question can help illustrate the increasing importance of music in society, regardless of any social, economic, or political issues that were happening at the time. 
2. 

## Manipulations
1. Both popularity and loudness had a default value of sum, however, these were manipulated to show the average popularity and loudness for each year.
2. 

## Analysis and Results
### Question 1
<img width="1153" alt="Screenshot 2023-04-19 at 12 03 12 PM" src="https://user-images.githubusercontent.com/82818412/233134333-b9a49f5b-9f3b-4d6b-a74c-4ba036d4bd5e.png">
<img width="1153" alt="Screenshot 2023-04-19 at 12 03 35 PM" src="https://user-images.githubusercontent.com/82818412/233134363-9ba26f2d-7040-4e8b-80ae-d60377b0d97d.png">
The average popularity bar for each year steadily grew in height, and the color that represented the average loudness for each year steadily grew to a darker red. The data analysis shows that both music popularity and loudness increased over time, suggesting that society increasingly values and prefers louder music. Further, it is interesting how music popularity in general continued to grow so consistently, even through major global events such as world wars.

### Question 2
<img width="1053" alt="Screenshot 2023-04-24 at 2 06 36 PM" src="https://user-images.githubusercontent.com/82818412/234079726-a32ff618-c7c5-48b9-b4bb-bd2407ab921b.png">

## Tableau Packaged Workbook

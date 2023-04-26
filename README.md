# MIST4610 Group Project 2
## Team Name and Members
We are team 21482_4. <br>

### Team Members <br>
* [Jimmy Chancellor](https://github.com/JChancello/) <br>
* [Austin Crispo](https://github.com/austincrispo/MIST-4610-Project-2) <br>
* [Clayton Hoarell](https://github.com/claytonh153454/group-project2) <br>
* [Tabea Lent](https://github.com/tabealent/group-project-2) <br>
* [Mary Grace Tippett](https://github.com/mgtipp/MIST4610_project2)

## Dataset Description and Contents
The chosen dataset contains information on the 100 most popular songs worldwide on Spotify by year from 1921-2020. The data was sourced from Spotify Web API and posted to the website [kaggle](https://www.kaggle.com/datasets/ektanegi/spotifydata-19212020). The dataset contains one csv file called data.csv and is comprised of 169909 rows and 19 columns. 
<br><br>
9 columns are of decimal type, 6 are of integer type, and 4 are of type String. The primary key identifies a given track with the ID of the track generated by Spotify. Acousticness, danceability, energy, instrumentalness, valence, liveness, and speechiness range from 0 to 1 describing the named characteristics of the track. Duration_ms is an integer column that ranges from 200k to 300k. Popularity ranges from 0 to 100, tempo ranges from 50 to 150, loudness ranges from -60 to 0, and year ranges from 1921 to 2020. Two attributes, mode and explicit, have a value of either 0 or 1 to specify whether the track is in a minor/major key and explicit/not explicit. The key attribute ranges from 0-11 starting on C as 0, C# as 1, and so on. Another attribute lists the name(s) of the artists, release_date names the date of release in yyyy-mm-dd format, and the name attribute lists the name of the song. Using this data, we can analyze certain questions.

## Generated Questions
1. How has music popularity changed from 1921 to 2020, and what is the relationship between music popularity and track loudness throughout the years? <br>
This question can help illustrate the increasing importance of music in society, regardless of any social, economic, or political issues that were happening at the time. Making a new song costs a LOT of money and takes a ton of time-- analysis of the output of this question can be taken from a business perspective in order to better predict the characteristics that will make a new song popular. This will help remove the "what if" aspect or fear factor around whether or not a song will actually profit.
2. How has track popularity and energy changed over time from 1921 to 2020 as well as their relationship to one another? <br>
This question can display the hand in hand relationship of popularity and energy in music. This shows that until very recently, the more energetic a song was the more popularity it gained. As well has in recent years how the popularity of music changes very quickly.

## Manipulations
1. Both popularity and loudness had a default value of sum, however, these were manipulated to show the average popularity and average loudness for each year. 
2. Like manipulation number 1, energy and popularity had a default value of sum, but these were manipulated to show the average energy and average popularity over time. 

## Analysis and Results
### Question 1
<img width="1153" alt="Screenshot 2023-04-19 at 12 03 12 PM" src="https://user-images.githubusercontent.com/82818412/233134333-b9a49f5b-9f3b-4d6b-a74c-4ba036d4bd5e.png">
<img width="1153" alt="Screenshot 2023-04-19 at 12 03 35 PM" src="https://user-images.githubusercontent.com/82818412/233134363-9ba26f2d-7040-4e8b-80ae-d60377b0d97d.png">
The average popularity bar for each year steadily grew in height, and the color that represented the average loudness for each year steadily grew to a darker red. The data analysis shows that both music popularity and loudness increased over time, suggesting that society increasingly values and prefers louder music. Further, it is interesting how music popularity in general continued to grow so consistently, even through major global events such as world wars. It is also interesting to note how, in the last year of data, popularity decreased suddenly. This might show a recent change in listener loudness preference. This is also the start of the COVID-19 pandemic, when people may have stopped or reduced their music listening.

### Question 2
<img width="1053" alt="Screenshot 2023-04-24 at 2 06 36 PM" src="https://user-images.githubusercontent.com/82818412/234079726-a32ff618-c7c5-48b9-b4bb-bd2407ab921b.png">
The chart suggests a trend that from the 1920’s to the 1950’s there wasn’t much evidence for energy and popularity having much correlation and both were highly variable.  In the mid 1950’s is when both measures started  to grow rapidly.  There was large growth in both energy and population until 2010 when the average energy hit a peak and began to have a relatively large decline while popularity continued to rise.  Popularity also hit a peak around 2019 and began to experience its largest decline since 1970. <br>
This change in relationship between average track energy and average popularity suggests the since, 2010 societies taste in music has favored songs with a lower track energy and has lead to the sharp increase in popularity. This could be attributed to changes in popular genres and style of music from the 2000s to the 2010s. Similarly, as 2019 marks a reverse in the trend of a lower track energy attributing to higher popularity could mean a shift again in the popular genre in a new decade. 

## Tableau Packaged Workbook
Download the packaged workbook [here](https://github.com/mgtipp/MIST4610_project2/blob/main/21482_GroupProject2.twbx)!

# W3-Pipelines_project

The project aimed to **enrichen a dataset through the use of APIs** and later create plots to conclude.


## Steps followed:

1. I created a jupyter file called **cleaning data**, where I open the raw data set I downloaded from kaggle; 'Top 50', which is a **csv file with the top 50 songs of 2019 from Spotify.**

2. In this same jupyter, I clean the csv file by dropping the columns I'm not going to use, check for null and duplicated values and rename the column names and values so all follow the same structure.

3. Once the data frame is clean I want to **enrichen it**. I do so by **choosing Spotify's API.**

4. Once the API I want to use is selected, I create another jupyter file **named Spotify api**, where I explore it and choose the relevant information I would like to extract to incorporate to my clean data frame.

5. I have chosen to enrichen it with **two other columns** named **followers** which refers to the artist followers on Spotify and another one named **picture**, where there is a url of the artists Spotify picture so it can add something more visual to the data frame.

6. At last, I created the third jupyter file named data representation were I plot all the graphs relating the results and trying to extract conclusions.


The main conclusion is that the **artist of the year was Ed Sheeran**. He had the most songs on the chart (4), being the most popular genre dance-pop and pop, where all of them fell into the pop category. He also has the most followers on the app.
On a second note, relating other features, we extract the following conclusions;  most of the songs have a low value for beats per minute and a high value for danceability. And most of the songs have a medium length.



## Challenges faced

The main fallback I faced was the use of the API which was the projects main goal.
It was my first time working with APIs so everything was very new. I first couldn't join the client id and the secret key in order to get a token to access the endpoints given by the API in order to get the information I needed.
Secondly, it took me a while to figure out how to access correctly information with a list and not an individual value.

![Getting Started](./spotify.png)


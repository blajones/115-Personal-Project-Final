# 115-Personal-Project-Final
# Motivation
At the beginning of the Major League Baseball season, I started playing on an app called Beat The Streak. The objective of the game is to beat Joe Dimaggio's hit streak of 56 games. Every day, you have the option to pick one or two players to get a hit during their games. If they get a hit, your streak continues, while if someone doesn't get a hit, your streak resets. The Beat The Streak app also comes with a bunch of stats that tell you the ERA of a pitcher, the batters batting average, who's playing at home or away, etc. When I first started playing, I picked Houston Astros shortstop, Carlos Correa to get a hit. That night, he failed to hit. I ended up picking him again about a week later, but this time he reached base. While the Beat The Streak app comes with a lot of stats, I was curious whether there was a pattern a batter followed when hitting. I wondered if a batter got a hit most games earlier in the season over the course of his career or later in the season. I wondered if there was a pattern at all. 

# Data Process
For my experiment I chose to research Carlos Correa and his batting patterns. To get a full batting history/data for this player, I went to https://www.mlb.com/player/carlos-correa-621043?stats=gamelogs-r-hitting-mlb&year=2018. What is noticeable in this link is the last 4 digits. That is the year the batting logs are from. On the MLB website you can choose a player and a year from their career to look at. When I was making my data set, I copied and pasted the entire batting log for each season Carlos Correa was in the MLB. Then I deleted all the stats that I didn't believe mattered to the project. I kept stats such as At Bats, Hits and Opponent. Next I edited each column so syntax and cells were all similar. After I did my initial cleaning, I added columns for the Day the At Bats and Hits took place. The Day stands for the number of the game played. I also created a yes/no column for every year, where it would give me a 1 if Correa got a hit that day, or 0 if he didn't. 
Steps:
1. Go to MLB.com
2. Search for team and then player (I chose Houston Astros and then Carlos Correa)
3. Choose year 2020 (2021 just began so it is not relevant)
4. Copy the entire batting log into an excel file
5. Delete all columns except for AB, H, and Opp
6. Repeat steps 3-5 until all years of the players career has been copied and edited
7. Delete the total sections in the rows in the excel spreadsheet
8. This is not necessary but format the cells so the fill color, borders, and font are all the same
9. Make columns titled Day and then year to document the games played in each year
10. Makes columns titled Y/N and then year to document whether the player got a hit that day

# Visualization
These first visualizations show the amount of hits Carlos Correa got in each game. I could have also made these in a bar graph form.

![image](https://user-images.githubusercontent.com/79551443/115945162-3efc9d80-a46f-11eb-8677-fa10640a2f48.png)
![image](https://user-images.githubusercontent.com/79551443/115945137-170d3a00-a46f-11eb-9d82-5fdc976f34bc.png)
![image](https://user-images.githubusercontent.com/79551443/115945171-4a4fc900-a46f-11eb-9a03-a43fda632032.png)
![image](https://user-images.githubusercontent.com/79551443/115945181-55a2f480-a46f-11eb-9d53-4eee2dc0913f.png)
![image](https://user-images.githubusercontent.com/79551443/115945191-5d629900-a46f-11eb-874f-e61436fdab18.png)
![image](https://user-images.githubusercontent.com/79551443/115945197-63f11080-a46f-11eb-9b07-15ebc30d5126.png)

This next line graph shows if Correa got a hit (y/n column) in the game he played in. 2020 is the clearest visualization. As you can see, Correa usually went on streaks of three games with a hit, and then had one or two games in between without a hit. He also went on two very large hitting streaks to begin the year.

![image](https://user-images.githubusercontent.com/79551443/115945258-baf6e580-a46f-11eb-937a-98cfbbdc1f9f.png)

These visualizations are a matrix of first the amount of hits per game and then whether he got a hit or not. There is not really a correlation between the amounts of hits per game for each year. There is a stronger correlation when comparing whether he got a hit in a game or not.

![image](https://user-images.githubusercontent.com/79551443/115945350-36589700-a470-11eb-9ff2-d14db26a9665.png)
![image](https://user-images.githubusercontent.com/79551443/115945356-41132c00-a470-11eb-9bae-8ac38fadbf80.png)


# Analysis
For one of my analysis, I used a box plot. I used a box plot to find the outlier in At Bats for every year. Sometimes in baseball, players can have six or more at bats, which is rare, and sometimes they can have none because they got walked a lot or hit by a pitch. My objective was to find these outliers and match them with the hits, or lack there of that day. In my analysis, I found that the mean number of at bats for Correa was usually around four. In 2020, it was three. In every year, he had at least one game with 6 at bats OR none at all. When he had five or more at bats, he usually had one or more hits in a game. The less amount of at bats, the less chance for hits. The 2017 box plot was the most interesting to me. The plot was almost perfect, with outliers at one and six. The mean looks like it is directly four and the quartiles looked symmetrical. The quartiles were almost perfectly on three and five. To me, this means this was a balanced year for either Correa or the Astros. Because of this balance, I believe it would have been the best year to find a pattern in hits for Carlos Correa.

![image](https://user-images.githubusercontent.com/79551443/115945462-cdbdea00-a470-11eb-8e30-c60b037fe0e5.png)




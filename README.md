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

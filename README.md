# The Impact of NFL Injuries on Players

## Table of Contents

- [Motivation](https://github.com/KirkGolliher/nfl-injuries#Motivation)
- [Data Questions](https://github.com/KirkGolliher/nfl-injuries#Data-Questions)
- [Data Sources](https://github.com/KirkGolliher/nfl-injuries#Data-Sources)
- [The Process](https://github.com/KirkGolliher/nfl-injuries#The-Process)
- [Final Project Link](https://github.com/KirkGolliher/nfl-injuries#Final-Project-Link)

## Motivation

I have chosen this topic because injuries are so impactful in sports. I’ve always been curious with what happens to players once they obtain a significant injury and how much it impacts their statistics once they recover. I personally have never experienced an injury like this, but I have seen many players have their careers cut short due to major injuries. It’d be interesting to see the factors that play a role in this happening.

## Data Questions

1) Which significant injury occurred most often in a span of four NFL seasons?
2) Which offense position group has the highest rate of injuries? 
3) Within each position group, which injury is more common? 
4) Is field type a major factor in certain injuries? (grass vs. turf) 


## Data Sources

- [Pro Sports Transactions](https://www.prosportstransactions.com/football/Search/Search.php) was used for gathering the players and their specific injuries.
- [Advanced Sports Analytics](https://www.advancedsportsanalytics.com/nfl-raw-data) was used to obtain player's game stats for the past three seasons (2019-2022).

## The Process
<details>
<summary>Data Acquisition</summary>
<br>
I found two sources of data for this project. My first source (Pro Sports Transactions) provided me with the injury reports for players. This showed me the date of the report, player name, team, and the injury. This is what I used to find the players, and it allowed me to search the specific injury. After searching for the specific injury, I scraped the website to obtain the data. I had to do this three total times and each time had 10+ pages to be scraped. 
<br><br>
The second source (Advanced Sports Analytics) was a CSV file that contained raw NFL data. This source provided me with information for each player's statistics in each game. The data started at the beginning of the 2019 season. The challenge with this source was to clean it and figure out exactly what to use from it since I could only use two season's worth of data.
</details>

<details>
<summary>Data Cleaning/Organizing</summary>
<br>
Because of the scraping, I had several dataframes I was working with. I had to figure out how to correctly merge my two data sources together and to get them ready for that. I had to work on datetimes, add new columns, and perform many for loops to get where I needed to be. The biggest challenge in this section is that I went back and forth on the different routes that I wanted to take, but finally settled on what I thought would give me the best chance to succeed. 
</details>

<details>
<summary>Creating Dashboard</summary>
<br>
I decided to go with Tableau for this project. It was simple getting all of my data loaded and ready to get my visuals going. Trying to figure out the right visuals and getting more variety besides the classic bar chart was a tough challenge in this stage of the project. I had to ensure that my story flowed right and told what I wanted from this. The story component of Tableau came in handy because that allowed me to create all of my slides within one program.
</details>

## Final Project Link
To view the final project through Tableau, click [here](https://public.tableau.com/app/profile/kirk.golliher/viz/injuries_16728599986190/Story1)

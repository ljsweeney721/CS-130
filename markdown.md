# Analying the Decline of NBA Home Court Advantage
## Data Sources: 
* The primary dataset used is the [NBA all time stats](nbaallelo.csv) file.
* The data contains over 126,000 professional basketball games played from 1946 through 2015.
## Data Preparation and Cleaning
* I created my own column called decade to group games up by decade for my analysis
* I made a Win column by taking the game_result column and making the wins 1 point and a lose 0 points
* Lastly, I created the Close Game column which finds the difference bwetween pts and opp_pts. This column was created for games that are less then or equal to 3 point margin
## Assumptions
* I assumed averaging data across a decade provides a good representation of my data and I assumed all data used was accurately reported
## Limitations
* My sample size was a limitation, as the 1940 decade is included but played fewer games against random teams, which can skew that decades results and make the entire markdown more volatile
* The analysis caannot take into accounts like arena capacity, travel distance, an event in the city, back to back games, etc.

# Article
The NBA home court advantage is one of the more underrated, yet most powerful factors in sports. For decades, the energy level of the home crowd, combined with the slugglishness from the high volume of games, created one of the most polarizing factors in a game
However, taking a look into the data would reveal that this once thought major advantage is not being used the same, as the rate of wins at home, especially in close games, is declining. With NBA talent peaking at an all time high, you would think this would not be the case. This look at game data from the 1940s to the 2010s shows that as the league became more even and more standardized, the advantage of playing at home has slowly faded.
### The Overall Decline
![Overall Decline of Home Court Advantage](First_Chart/CS-130Project) 
![Overall Home Win Rate](../images/First_chart.jpeg)
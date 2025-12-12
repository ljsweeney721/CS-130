## Methodology
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
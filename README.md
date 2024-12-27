# Project-Extracting-TV-Data-Insights-
This project explores the Super Bowl's appeal beyond football, showcasing thrilling games, dramatic comebacks, and extravagant ads. It highlights unforgettable halftime shows featuring top musicians, making the Super Bowl a cultural phenomenon that captivates audiences worldwide with its blend of sports and entertainment.

Tasks:
Explore Super Bowl data to uncover insights about TV viewership, game outcomes, and halftime shows.

Has TV viewership increased over time? Save your answer as a boolean variable named viewership_increased.
How many matches finished with a point difference greater than 40? Save your answer as an integer named difference.
Who performed the most songs in Super Bowl halftime shows? Save your answer as a string named most_songs.

# The Data

Three datasets have been provided, and summaries and previews of each are presented below.

### 1. **halftime_musicians.csv**

This dataset contains information about the musicians who performed during the halftime shows of various Super Bowl games. The structure is shown below, and it applies to all remaining files.

| Column       | Description                                                                                  |
|--------------|----------------------------------------------------------------------------------------------|
| `'super_bowl'` | The Super Bowl number (e.g., 52 for Super Bowl LII).                                         |
| `'musician'`   | The name of the musician or musical group that performed during the halftime show.           |
| `'num_songs'`  | The number of songs performed by the musician or group during the halftime show.             |

### 2. **super_bowls.csv**

This dataset provides details about each Super Bowl game, including the date, location, participating teams, and scores, including the points difference between the winning and losing team (`'difference_pts'`).

### 3. **tv.csv**

This dataset contains television viewership statistics and advertisement costs related to each Super Bowl.

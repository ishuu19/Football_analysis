# Football Match Analysis

## Project Description

This project involves analyzing football (soccer) match data to derive various insights and visualize trends using Python and the pandas library. The dataset used contains information about football matches including the date, home team, away team, home score, away score, and the tournament in which the match was played.

## Data Preprocessing

- The initial dataset is read from a CSV file named 'results.csv'.
- The columns of interest are selected: "date", "home_team", "away_team", "home_score", "away_score", and "tournament".
- The "date" column is converted to datetime format.
- The data is filtered to include matches only from the years 2011 to 2020.

## Analysis and Visualization

### Table 1: Winning Percentage by Team by Year (Table 1a)

- The winning percentage of each selected team is calculated for each year from 2011 to 2020.
- The results are summarized in a table showing the winning percentage for each team by year, along with the average win percentage across all years.

### Table 2: Average Number of Goals per Match by Year by Team (Table 2a)

- The average number of goals per match scored by each selected team is calculated for each year from 2011 to 2020.
- The results are summarized in a table showing the average goals per match for each team by year.

### Correlation Analysis

- The correlation between the winning percentage (Table 1b) and the average goals per match (Table 2a) for each team is calculated.
- Scatter plots are created to visualize the relationship between winning percentage and average goals per match for each team.

### Additional Analysis

- The winning percentage for each team when winning the previous two matches, one of the previous two matches, and losing the previous two matches is calculated.
- The results of matches played in the home country of each team are analyzed, including the distribution of match results and the total scores in home turf.
- Bar charts are created to compare the overall winrate and home winrate for each selected team.

## Visualization of Economic Data

- Economic data related to house prices, construction spending, interest rates, and mortgage rates is retrieved using the FRED API.
- Time series plots are created to visualize the trends in these economic indicators over time.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- fredpy

## Running the Code

- Ensure all required libraries are installed.
- Download the 'results.csv' dataset.
- Run the Python script to execute the analysis and generate visualizations.

## Author

Anayed Hossain Eshan

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

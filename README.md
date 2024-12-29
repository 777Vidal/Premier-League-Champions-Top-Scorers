# Premier League EDA: Analyzing Top Scorers and League Outcomes

## Overview
This project analyses Premier League data to explore the relationship between player positions, top scorers and league outcomes. By examining whether having the league's top scorer correlates with winning the league, we gain insights into the importance of individual contributions versus team dynamics.

The dataset includes:
- Premier League champions from 1992-93 to 2023-24.
- The top scorer for each champion team and their position.
- The league's top scorer and their position.
- Indicators of whether the league's top scorer was from the champion team.

## Goals
1. Analyse if having the league's top scorer is crucial for winning the Premier League.
2. Explore the positions of players who are top scorers and their impact on team success.
3. Visualise trends in top scorer positions and their influence on championships.

## Dataset
The dataset was created manually and contains the following columns:
- `Season`: The Premier League season.
- `Champion`: The team that won the league.
- `Champion Top Scorer`: The top scorer of the champion team.
- `Champion Top Scorer Position`: The position of the champion team's top scorer (e.g., FW, ST, CM, etc.).
- `League Top Scorer`: The player with the most goals in the league.
- `League Top Scorer Position`: The position of the league's top scorer.
- `League Top Scorer in Champion Team`: Boolean value indicating if the league's top scorer played for the champion team.

## Key
- ST = Striker
- FW = Center Forward
- Winger = Right Winger/Left Winger
- AM = Attacking Midfielder
- CM = Center Midfielder

## Analysis & Visualisations
### Key Visualisations:
1. **Did the League's Top Scorer Play for the Champion Team?**
   - A bar chart shows how often the league's top scorer was from the champion team.

2. **Positions of League Top Scorers in Champion Teams**
   - A bar chart visualising positions (e.g., ST, FW, AM) of players who were both the league's top scorer and part of the champion team.

3. **All League Top Scorer Positions**
   - A bar chart comparing the positions of all league top scorers, regardless of whether their team won the league.

4. **Positions of Champion Team's Top Scorers**
   - A bar chart showing the distribution of positions for the champion team’s top scorers.

5. **Proportion of Seasons with League Top Scorer in Champion Team**
   - A pie chart showing the proportion of Top Scorers and if they won the league or not.

6. **League's Top Scorer in Champion Team Over Time**
   - A lineplot graph visualising over time if the top scorer played for the champion team.

## Results
- The visualisations help determine the frequency of champions with league top scorers.
- They explore whether specific positions (e.g., strikers, midfielders) are more critical for league-winning performances.
- Insights are drawn about team composition and the roles of star players in achieving league success.

## Tools Used
- **Python**: For data processing and analysis.
- **Pandas**: For handling the dataset.
- **Matplotlib** and **Seaborn**: For creating visualisations.

## Conclusion
This project provides an in-depth look at the relationship between top scorers, their positions, and team success in the Premier League. By analysing decades of data, it uncovers patterns that offer valuable insights into the dynamics of league-winning teams.

## Future Work
- Expand the dataset to include assists and other performance metrics.
- Analyze defensive contributions and their impact on league success.
- Investigate correlations between spending and league performance.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

Thank you for exploring this project! Contributions and suggestions are always welcome.


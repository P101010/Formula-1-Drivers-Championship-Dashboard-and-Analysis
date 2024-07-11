# Formula-1-Drivers-Championship-Dashboard-and-Analysis
## Introduction
Our main objective is to introduce the sport of F1 through various Tableau visualizations and tell the story of the 2021 season’s battle for the championship between Lewis Hamilton and Max Verstappen. Using car-level data, we highlight the underdog story of RedBull Racing and Max Verstappen against the Mercedes Team with Hamilton.

The data was cleaned and processed using Python’s Pandas library and connected to Tableau. The project consists of two dashboards and a story with six chapters, each utilizing the same dataset for different visualizations.

## Dashboards and Story Visualizations

### Story - F1 History (1950-2021)
- Provides introductory stats and visualizations to help newcomers understand F1.
- Contains stats about past winners, both drivers and teams.
- Includes a world map of all circuits with interactive hover effects to show total races.
- Users can filter stats to view information about their favorite racer or team.

### Dashboard 2 – F1 2021 Season
- Highlights key moments and statistics of the 2021 season, known as one of the best in recent times.
- Interactive filters allow users to view details by race number, circuit stats, GP name, grid standings, and lap time deltas.
- Visualizes telemetry data such as throttle responses, braking, engine RPMs, DRS usage, gear data, and speeds.
- Displays race pace and tire strategies based on user-defined filters.

### Story - F1 2021 Battle for the Championship
- Narrates the events of the 2021 season, focusing on the battle between Hamilton and Verstappen.
- Uses graphs for lap progression, fastest laps, and driver pace with box plots and line plots.
- Annotations highlight pit stops, tire strategies, safety car deployments, and other key events.
- Discusses the impact of driver strategies and track conditions on race results.
- Highlights Max Verstappen’s underdog story and his championship win.

## Datasources
- **Kaggle Data Source**: [Formula 1 World Championship (1950-2020)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
  - `constructor_results.csv`: Race results of teams per season.
  - `races.csv`: Lap-level data of all races from 1950-2021.
  - `results.csv`: Results of each race till 2021.
  - `lap_times.csv`: Lap times in milliseconds for each race from 1950-2021.
  - `circuits.csv`: Data about all F1 circuits worldwide.
  - `drivers.csv`: Data of all racing drivers participating in at least one F1 race.
  - `constructors.csv`: Data of all racing teams participating in at least one F1 season.
- **Ergast API**: [Ergast API](http://ergast.com/)
  - Provides telemetry datasets, including tire data and engine RPM data.
  - Utilized for visualizing car-level data for specific race visualizations.

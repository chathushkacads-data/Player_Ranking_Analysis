#  Player Ranking Analysis

This project focuses on processing and analyzing ICC ODI player rankings using Python and the Pandas library.

##  Project Goals
* **Data Cleaning**: Removed unnecessary columns like "Best_Against" and "Best_Date" to focus on core metrics.
* **Country Filtering**: Filtered player rankings to create specific datasets for individual nations, such as New Zealand.
* **Statistical Analysis**: Calculated the average points per country to compare performance across different teams.
* **Automation**: Used programmatic loops to save country-specific data into organized files.

##  File Structure
* **odi_batting_rankings.csv**: The source dataset containing global player rankings.
* **ODI_Ranking_Analysis.ipynb**: The main Jupyter Notebook containing the data processing and analysis logic.
* **CountryBy_Players/**: A directory designated for storing the generated CSV files for each country.
* **NewZealand_Players.csv**: A sample output file containing filtered data for players from New Zealand.

## Disclaimer
Note: The data provided in this repository is for educational purposes and may not be 100% accurate or up-to-date with current real-time rankings.
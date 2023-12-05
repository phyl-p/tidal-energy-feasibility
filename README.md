# tidal-energy-feasibility
Jupyter Notebook script for web scraping and preprocessing data from national data buoy center. 

This notebook covers:
1. Scraping an html file downloaded from historical record page of national data buoy center (https://www.ndbc.noaa.gov/historical_data.shtml) for download links. The purpose of collecting download links is mainly to find out what stations are available (by their station ids) through parsing these links.
2. Scraping the coordinates of each station
3. Downloading different types of data for each station (standard meteorological)/saving select data into files and organized into folders by type of data/station id/year
4. Systematically reading in data scraped and performing sql like queries for temporal/statistical analysis

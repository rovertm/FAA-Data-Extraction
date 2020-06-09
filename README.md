# faa_repair_stations


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

* BeautifulSoup library for web scraping. Please see docs and install instructions here: https://www.crummy.com/software/BeautifulSoup/bs4/doc/

Other: standard Python libraries across Anaconda distribution.

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

I was interested in examining the less-publicised small businesses of the commercial aviation sector - component repair stations.
The FAA delegates specific ratings for repair stations and their personnel. From experience in the industry I understood the small specialist nature of the component repair world, though with the largest recession to ever hit the aviation industry 
I wanted a data-driven understanding of the landscape to help understand economic consequences.

Here are the questions I considered through the analysis:

1. How many FAA repair stations are in each U.S. state?
2. For the states with the most repair stations, what are their ratings (specializations)?
3. What is the composition of small businesses (< 20 employees) to large businesses across the repair station landscape?
4. What percentage of the repair station workforce is skilled (certificated), and how does composition vary from small to large businesses?

## File Descriptions <a name="files"></a>

Files include a single .ipynb and three supporting .csv files.

.ipynb: Contains all code and visualizations. The .ipynb flows linearly from data collection, cleaning & processing, to modeling and visualizations.

.csv files: Source data (initial_export_faa.csv); webscrape results (scraped_stations.csv); and final consolidated data set after collecting and scraping (all_data_faa.csv) 

## Results<a name="results"></a>

Please find the results summarized in the article [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The source data for this project originated from the FAA's website: https://av-info.faa.gov/repairstation.asp
The initial export from the site - for this project - was done on 05/24/2020. The data is updated weekly by the FAA, and may vary
by the time you are exploring the files.

All code is open for any and all usage.
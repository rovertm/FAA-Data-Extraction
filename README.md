# faa_repair_stations


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)
5. [View the notebook](#notebook)

## Installation <a name="installation"></a>

* BeautifulSoup library for web scraping. Please see docs and install instructions here: https://www.crummy.com/software/BeautifulSoup/bs4/doc/

Other: standard Python libraries across Anaconda distribution.

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

I was interested in examining the composition of FAA component repair stations in the United States.

Here are the questions I considered through the analysis:

1. How many FAA repair stations are in each U.S. state?
2. For the states with the most repair stations, what are their FAA ratings (specializations)?
3. What is the composition of small businesses (< 20 employees) to large businesses across the repair station landscape?
4. What percentage of the repair station workforce is skilled (certificated), and how does composition vary from small to large businesses?

The intent of the analysis was observational understanding.

## File Descriptions <a name="files"></a>

Files include a single .ipynb and three supporting .csv files.

.ipynb: Contains all code and visualizations. The .ipynb flows linearly from data collection, cleaning & processing, to modeling and visualizations.

.csv files: Source data (initial_export_faa.csv); webscrape results (scraped_stations.csv); and final consolidated data set after collecting and scraping (all_data_faa.csv) - please use this data set for your own projects!

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The source data for this project originated from the FAA's website: https://av-info.faa.gov/repairstation.asp
The initial export from the site - for this project - was done on 05/24/2020. The data is updated weekly by the FAA, and may vary
by the time you are exploring the files.

All code is open for any and all usage.

## View the notebook <a name="notebook"></a>

View the notebook at Jupyter's NBviewer site, [click here.](https://nbviewer.jupyter.org/github/rovertm/faa_repair_stations/blob/master/faarepair_stations.ipynb)

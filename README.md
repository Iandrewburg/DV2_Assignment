# Bird Observations in Oklahoma and Arkansas from January 2022 through November 2023
---
This project takes a look at bird observations from Oklahoma and Arkansas in the United States. These states are situated next to each other, but have very different observation patterns for certain species of bird. These could be connected to weather patterns and migration streams. 

The data was collected from the Cornell University's Ornithology Lab. The Cornell Lab of Ornithology launched a digital project named eBird for the purpose of acquiring bird observation data from birdwatchers around the world, and the project was a huge success. Large quantities of data are collected and submitted to this platform everyday. For more information about eBird, follow this link! **[About eBird](https://ebird.org/about)**. 

eBird has large data storages, and allow researchers access to this treasure-trove of bird data. I submitted a request to this database for academic purposes, and was granted access for projects like this. Once grated access, the data can be found at the following link: **[eBird Data](https://ebird.org/data/download/ebd)** As the datasets are extremely large, they are submitted to the research as a text file. From here, I transformed the .txt file into a .csv file. The .csv file was too large to upload to github, so it was then zipped for easier storage. An unzipping function is included in the beginning of this code to unzip the .csv file from the Github link, and read the .csv into a dataframe.

This project identifies and creates visuals for the following subjects:
- Top 10 observed species by state
- Monthly time series observations of the most observed species by state
- Monthly time series state comparative observations for a selected species
---

# DHCAL-Data-Analysis-for-Pion

Analysis of Digital Hadron Calorimeter test beam data with Pandas and OpenCV libraries in addition to ROOT which is a software framework for data analysis developed by CERN.

First, the data is in an Ntuple file. It is converted to Pandas DataFrame and saved as csv file for further processing. The data includes the coordinates of the hits and events from when they occurred. The data has been turned into a data frame. Hits in the first 39 layers of the calorimeter were used in the analysis. Some selections were made in the data to avoid noise in the data and to analyze pion events. The opencv library used in computer vision applications was used to get rid of electronic noise.

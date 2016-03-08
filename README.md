# CR1000-Instrument-Analysis
Group code for analyzing data collected from environmental sensors using Campbell Scientific CR1000 dataloggers operated by UBC Eco

##Introduction
Commonly instruments for environmental monitorring are connected to CR1000 data loggers to collect and compile data from many instruments.
This repository is going to serve as a place for people to share and improve R code for analysing data collected on CR1000 data loggers.

The first important piece of code addresses the formatting of the time vector associated with any csv file and needed for plotting

CR1000IA_tv.r

The second piece of code address the need to make a simple plot of all data to view and inspect for clear problems

CR1000IA_INST_BASIC.r

The third piece of code addresses the common requirement to average data by some time period

CR1000IA_INST_AVE.r

The fourth piece of code addresses some common interparative analysis e.g simple correlations

CR1000IA_INST_ANALY.r

An example data file is available at....Below is a description of some issues with this data set that need to be addressed in the code. These
Include, missing data points, complicated time stamps (changes in time stamp) etc. TO BE CONTINUED

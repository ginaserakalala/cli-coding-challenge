# CLI Application

## Overview
A Python CLI App that uses a terminal to draw graphs that outputs
Dates (as keys) and the number of active users on those dates (as values)
The app is also able to filter the data by Start date and end date

Usage

Use data file provided with two columns either comma or space separated.
The first column(dates) is your labels, the second column is a numeric data of active users

termgraph [datafile]

Help: termgraph -h 

usage: termgraph.py [-h] [(optional arguments)] [filename]

positional arguments:
  filename              data file name (comma or space separated)
   arguments:
     --calendar            Calendar Heatmap chart
    --start-dt START_DT   Start date for Calendar chart

  
## Requirements

This project manages its dependencies using pip
Install the following to run the app:
Linux OS                        Mac OS
sudo apt-get install python3.6 ,brew install python@3.8

pip3 install colorama

pip install termplotlib

python -m pip install requests

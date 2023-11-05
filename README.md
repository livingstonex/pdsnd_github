### Date created
Created on the 5th of October, 2023.

# Data Exploration with pandas on Bikeshare Data across 3 cities
_A Python project using pandas to explore bikeshare data._


# Project Overview

This project focuses on using python to analyse and explore bikesahre data collated from three different cities. We would be leveraging python modules and libraries such as numpy and pandas for the more data analytical aspects of this exploration


### Running the program

You can type in 'python bikeshare.py' on your terminal to run this program.

### Program Details

The program takes in user typed input for;
1. City (e.g. Washinton), 
2. Month for which the user intends to view data (e.g. May. It also includes an 'all' option), and
3. Day for which the user would like to view data (e.g. Thursday. This also includes an 'all' option).

Upon receiving the input form the user, the program prints the following details:

* Most popular month
* Most popular day
* Most popular hour
* Most popular start station
* Most popular end station
* Most popular combination of start and end stations
* Total trip duration
* Average trip duration
* Types of users
* Types of users by gender (if available)
* The most common birth year amongst users (if available)

At the end, the user is prompted with the choice of restarting the program or not.

# Required language and packages
* Language: Python 3.6 or above
* Libraries: pandas, numpy, time

# Files used

* new_york_city.csv - This dataset contains all bikeshare information for New York city.

* chicago.csv - This dataset contains all bikeshare information for Chicago city.

* washington.csv - This dataset contains all bikeshare information for Washington city. It's important to not that this does not include the 'Gender' or 'Birth Year' data.

# Built with

* [Python 3.6.6](https://www.python.org/) - Core language.
* [pandas](https://pandas.pydata.org/)
* [time](https://docs.python.org/2/library/time.html)
* [numpy](http://www.numpy.org/)

  
# Credits
* [pandas docs](http://pandas.pydata.org/pandas-docs/stable/) - pandas documentation was immensely helpful in understanding the implemention of pandas methods used in this project.
* [Udacity](https://udacity.com) - Udacity's Data Analyst Nanodegree program and their instructors were extremely helpful while I was pursuing this project.


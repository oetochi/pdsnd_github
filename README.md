# Project Title

### Analysis of Bikeshare Data From 3 US Cities

# Description

This project is an indept user interactive analysis of historical bikeshare data from 3 major US cities (Chicago, New York City and Washington DC).

The user answers some questions like which city to analyse, the month of choice, etc, and on the basis of the feedback received, the program outputs insightful information including some descriptive statistics.

In it, we explored key trends like the most common hour, day, and month among the riders.
We digged deep into the most popular start and end destinations and the results were amazing!
Why not check it out yourself!


# Getting Started
## Dependencies
 - python 3
 - numpy library
 - pandas libarary
 - Machine running on Windows 8 or higher
 
 
# Installing
The bikeshare.py program can be downloaded from my repository


# Executing program
### To run this program successfully and get the intended result, do the following:
 - import numpy and pandas libraries
 - load the csv data files of the 3 cities into python 3 like this:

    **CITY_DATA = _{ 'chicago': 'chicago.csv',
              'new york city': 'new_york_city.csv',
              'washington': 'washington.csv' }_**


# Author

__Opara-Eze Tochi__

*@oetochi*


# Version History
0.1
Initial Release

# License

 This project does not require any licence. You can use or modify the codes here to help you in anyway you deem fit.


# Acknowledgments

### In executing this project, I got inspiration from the following persons and sources:

* Juno Lee - Python Instructor
* Richard Kalehoff - Version Control

[Realpython](https://realpython.com/python-formatted-output/)

Code Snippet

    print('{0} {1} cost ${2}'.format(6, 'bananas', 1.74))
    6 bananas cost $1.74

[Stackoverflow](https://stackoverflow.com/questions/47136436/python-pandas-convert-value-counts-output-to-dataframe)

Code Snippet

        df = pd.DataFrame({'a':[1, 1, 2, 2, 2]})
        value_counts = df['a'].value_counts(dropna=True, sort=True)
        # solution here
        df_val_counts = pd.DataFrame(value_counts)
        df_value_counts_reset = df_val_counts.reset_index()
        df_value_counts_reset.columns = ['unique_values', 'counts'] # change column names

[Stackoverflow](https://stackoverflow.com/questions/53086118/python-for-dummies-using-the-bakeshare-data)

Code Snippet

        # get user input for city (chicago, new york city, washington). HINT: Use a while  loop to handle invalid inputs
        cities = ('chicago', 'new york', 'washington')
        while True:
            city = raw_input('Which of these cities do you want to explore : Chicago, New York or Washington? \n> ').lower()

            if city in cities:
                break
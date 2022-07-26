# data-vis-fbi-hate-crime

Data Analysis of US Hate Crime from 1991 - 2020

## Technologies Used

- Python - Pandas, MatPlotLib
- Anaconda Navigator, Jupyter Notebook

## Features

- Data Analysis of US Hate Crime

## What I learned

- Create line and pie charts with matplotlib
- Create, Merge and Append DataFrames
- Create New Calculated Column in DF
- Conctenate DFs to Fill In Missing Dates

## Challenges

- When tryign to create a graph of total hate from data by bias, I kept getting
  an error when trying to plot the Trans data. I realized this was because the
  data didn't report any Trans Hate Crimes until 2013. All other bias types had
  data since 1991.

### Steps I followed to solve challenge:

1. Create new "empty" df with full date range (1991 - 2020)
2. Find years that were in my "empty" df that weren't in my existing df.
3. Concatenate the new years with my existing df.

## Future Improvements

- Look at ways to refactor
- Further analysis of hate crime in the US by state.

## Set-Up

My code and charts can be seen by viewing the "FBI Hate Crime 1991 - 2020.ipynb"
file in this repo.

## Credits

This project was created with the following datasets:

- [FBI Crime Data Explorer](https://crime-data-explorer.app.cloud.gov/pages/downloads)
- [statista's Resident population of the United States by race from 2000 to 2020](https://www.statista.com/statistics/183489/population-of-the-us-by-ethnicity-since-2000/)

## Preview

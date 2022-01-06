# Data analysis for the South Africa vs India 2021/22 series

## What is this about?
The goal of this project is to analyze and visualize the finer details of the South Africa vs India series and the players/squads participating in it from different angles.

## What are the main files?
As of now, there are 2 important files: [year_by_year.ipynb](https://github.com/hmshreyas7/sa-vs-ind-2021/blob/main/year_by_year.ipynb) that allows one to compare the batting averages of multiple batsmen in each year that they've played and [partnership_breakers.ipynb](https://github.com/hmshreyas7/sa-vs-ind-2021/blob/main/partnership_breakers.ipynb) that helps compare the average partnerships that bowlers have managed to break.\
In the former, the names of players and the number of players considered for comparison can be adjusted but might require some modifications with respect to the plot settings. As for the latter, using or changing the customizable parameters should be pretty straightforward. In both cases, however, the values for 'player' must be set accurately in the format shown. The exact player name with the correct initials can be found using [Cricinfo Statsguru](https://stats.espncricinfo.com/ci/engine/stats/index.html). The other parameters are only used for customizing the plot and can be set as desired.\
Although the purpose of this is to analyze players involved in this series, it can also be used for players from other countries that have played Test match cricket between March 8, 2004 to December 26, 2021.

## What are the dependencies?
* Python 3.10.1
* pandas 1.3.5
* matplotlib 3.5.1
* jupyter-notebook 6.0.1

## Where can the data to reproduce these results be obtained?
The ball-by-ball data for all Test matches between March 8, 2004 to December 26, 2021 was obtained from [Cricsheet](https://cricsheet.org/downloads/tests_csv2.zip). All the individual Test match files were then combined together using an [online tool](https://extendsclass.com/merge-csv.html).

## The purpose of using certain functions in the code is not very clear. Are there any references for these?
The roles of some functions may indeed be hard to figure out at first glance. Some references that might be useful for better understanding are:
1. [Sorting a dataframe](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html)
2. [Getting the year from a date](https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.year.html)
3. [Getting the list of a dataframe's index labels](https://www.geeksforgeeks.org/python-pandas-series-keys/)
4. [Finding the common values in multiple lists](https://stackoverflow.com/questions/28061223/python-how-to-find-common-values-in-three-lists/28061246)
5. [Plotting a bar chart](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.bar.html)
6. [Picking the right colors for data visualizations](https://learnui.design/tools/data-color-picker.html)
7. [Using groupby, cumsum, and shift to reset cumulative sum at different points](https://stackoverflow.com/questions/67017828/restart-cumsum-in-pandas-with-condition/67017916#67017916)
8. [Named aggregations](https://stackoverflow.com/questions/38174155/group-dataframe-and-get-sum-and-count/59421504#59421504)
9. [Drawing a horizontal bar chart](https://www.geeksforgeeks.org/draw-a-horizontal-bar-chart-with-matplotlib/)
10. [Making a single bar stand out with a different color](https://stackoverflow.com/questions/20394091/pandas-matplotlib-make-one-color-in-barplot-stand-out/20394326#20394326)
11. [Displaying value labels for each bar](https://stackoverflow.com/questions/30228069/how-to-display-the-value-of-the-bar-on-each-bar-with-pyplot-barh#comment86813015_30229062)
12. [Formatting a numeric string to always show 2 decimal places](https://stackoverflow.com/questions/1995615/how-can-i-format-a-decimal-to-always-show-2-decimal-places)

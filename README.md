# D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Introduction

As a data visualization specialist my task is to analyze the current trends shaping people's lives, as well as create charts, graphs, and interactive elements to facilitate the decision making process.

The editor wants to run a series of feature stories about the health risks facing particular demographics using the information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.  

The provided data set is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/), and includes data on rates of income, obesity, poverty, etc. by state. 

### Setting Up

*  The **html** and **Javascript** are the main files to run for analysis.

### Core Assignment: D3 Dabbler (Required Assignment)

![4-scatter](Images/4-scatter.jpg)

* A scatter plot was created using the `Healthcare vs. Poverty` variables.

* A scatter plot that represents each state with circle elements was created using the D3 techniques.  The graphic was coded in the `app.js` file. Data was pulled in the data from `data.csv` by using the `d3.csv` function. 

* State abbreviations in the circles have been included, along with the axes and labels

* The `python -m http.server` was used to run the visualization and the link to the web browser was part of the submission.

### Bonus: Impress the Boss (Optional Assignment)

Used D3 to create a responsive graph.

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

Included more demographics and risk factors. Placed additional labels in my scatter plot and gave them click events to help users decide which data to display.  Animated the transitions for circles' locations as well as axes ranges. 

* Hint: Binding all of the CSV data to circles allows for ease in determining x or y values when labels ae clicked.

#### 2. Incorporate d3-tip

While the ticks on the axes allow for the inference of approximate values for each circle, it's impossible to determine the true value without adding another layer of data.  The `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)— has been used to add tooltips to circles and dispay data.

![8-tooltip](Images/8-tooltip.gif)

* Aso Checked out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) on how to implement tooltips with d3-tip.

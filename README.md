# D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

As a data visualization specialist at a newsroom for a major metro paper, the task is to analyze the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System. 

The included data set is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/), but  a different data set can also be used. The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Initial Step

*  This homework utilizes both **html** and **Javascript** that are stored in the folder: **D3_data_journalism**.

### Core Assignment: D3 Dabbler (Required)

![scatter](D3_data_journalism/assets/images/scatter.jpg)

Created a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.  This graphic was coded in the `app.js` file, through pulling in the data from `data.csv` by using the `d3.csv` function.  The graphic includes:

* state abbreviations in the circles.

* created and situated axes and labels to the left and bottom of the chart.

* Note: `python -m http.server` was used to run the visualization and host the page at `localhost:8000` web browser.

- - -

### Bonus: Impress the Boss (Optional)

Created an interactive graphic using selected data.

![animated-scatter](D3_data_journalism/assets/images/animated-scatter.gif)

#### 1. More Data, More Dynamics

Included more demographics and risk factors. Placed additional labels in the scatter plot and gave them click events so that users can decide which data to display. Animated the transitions for circles' locations as well as the range of axes. (for two risk factors for each axis Or for three for each axis).

* Hint: Binding all of the CSV data to the circles can help simplify the detemnation of x or y values through clicking on the labels.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Entered tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element by adding tooltips to graphic circles and displaying each tooltip with the data that the user has selected. Used the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)— this plugin is already included in the D3_data_journalism directory.

![tooltip](D3_data_journalism/assets/images/tooltip.gif)

* Checked out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how to implement tooltips with d3-tip.

- - -
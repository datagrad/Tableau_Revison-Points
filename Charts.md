# Types of Charts

### Bar charts
* Bar charts are used for comparing data values or tracing changes in data over a period of time.
### Line charts
* Line charts are used for analysing data values over a period of time.
### Area charts
* An area chart is a line chart where the area between the line and the axis is shaded with a certain colour.
* These charts are used for representing the accumulated total values over a period of time and are the conventional way of displaying stacked lines.
### Box plots
* Box plots are quite effective when you want to compare the distribution of two quantitative variables.
* The constituents of a box plot are as follows:
    * The line inside the box denotes the median value, and 50% of the data lies both above and below that value.
    * The boundaries of the box denote the 25th and the 75th percentiles.
    * The whiskers denote the lowest and the highest values in the data set (excluding outliers).
    * Any observations lying below or above the whiskers are considered to be outliers.
    * Outliers are the data points that have absurdly high or low values than those of the other observations.

### Maps
* Maps is an online functionality provided in Tableau.
* To build a simple map, data source must contain location data (location names, or latitude and longitude coordinates). The map which contains points in each state, for example, is called a point map.
* The map which contains states filled with varying colour, for example, is called a filled map or a polygon map.

 

### Hierarchies
* A hierarchy of features, such as country, state and city, can be created to obtain richer visualisations using the same data set.

 

### Pie Charts
* Pie charts are effective tools for visualising a particular category as a ratio of the total available categories.

### Histograms and parameters
* Histograms plot quantitative data with ranges of data grouped into bins, which is done automatically by Tableau.
* Parameters allow you to control and provide values to pass into Tableau.
 
### Scatter plots
* Scatter plots are used to plot two quantitative variables against each other or two quantitative variables on a categorical variable.
 
### Dual-axis charts
* A dual-axis bar chart is used when the ranges of the quantitative variables differ significantly. 
* There are two y-axes, one on each side representing a quantitative variable.
* The categorical variable is represented on the x-axis.
 
### Stacked bar charts
* A stacked bar chart, also known as a stacked bar graph, is a graph that is used to break down and compare parts of a whole.
* Each bar in the chart represents a whole, and segments in the bar represent different parts or categories of that particular whole.


### Donut Charts
* A donut chart is a variation of a pie chart with a hole in the centre. This hole can be used to display additional information.
 
### Pareto Charts
* A Pareto chart is a combination of a bar graph and a line chart.
* The bars in this visualisation are arranged in descending order, while the line chart is a cumulative total of the values in the bar graph.
 
### Packed Bubble Charts
* A packed bubble chart contains multiple circles or bubbles in varying sizes and/or colors according to the data value in each bubble.
* Its main advantage is that you can easily see the values that stand out.
 
### Highlight Tables
* A highlight table is essentially a table, but it is different due to the following features. These features make it easy to read large tables:
* They generally contain numeric values.
* The background of each cell is coloured with an intensity corresponding to its value.
 
### Control Charts
* A control chart is a variation of a line chart containing additional horizontal lines called limits. These limits can be made dynamic if required. The lower and upper limits are calculated using the following two functions.
* WINDOW_AVG(): This function is used to calculate the average of the values of the variable in question. However, it will consider only the values present in the visualisation out of the total values present in the dataset.
* WINDOW_STDEV(): This function is similar to the WINDOW_AVG() function, except that it calculates the standard deviation of the values present in the visualisation.

### Motion charts
* A motion chart is mostly used to display changes in data over time. You can change the speed of the animation as well as the direction.
* ‘Show history’ is a highly useful option that enables you to see how the data values of a particular category and subcategory changed over a period of time.
 
### Bullet charts
* A bullet chart is a variation of a bar chart where you can find out if a certain measure of a categorical variable is less than, equal to or greater than the recommended value.
 
### Gantt charts
* A Gantt chart consists of a group of bars generally used to track the progress of each step in a project.
 
### Likert scales
* A Likert scale is a rating scale that is commonly used in surveys. For example, the values in a Likert scale can be:
* Strongly disagree
* Disagree
* Neither agree nor disagree
* Agree
* Strongly agree
 
### Likert scale charts
* A Likert scale chart is a modified bar chart used to visualize a Likert scale.

### Hexbin charts
* Hexbin charts, or hexbin maps, are called so because they consist of a large number of hexagonal ‘bubbles’.
* To create a hexbin chart, you need to use the HEXBINX() and HEXBINY() functions that are provided in Tableau.

### Treemaps
* Treemaps plot the quantitative variables for each category of the dimension.
* The values of the quantitative variables are represented by the size and the colour intensity of the plot.
* They can only accommodate two measures: one to control the size and the other to control the colour. 
* However, it can accommodate any number of dimensions, as it would only increase the number of rectangles on the treemap.



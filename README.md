# Visualizing Ride-Sharing Data 

## Visualization of Ride Share Data using Pandas Data Frames and MatPlotLib Overview

This project is to perform exploratory data analysis on approximately 8 months of ride-sharing data including: 
* inspecting the data
* merging data sets
* performing calculations
* creating data series and data frames. 

Matplotlib will then be used with the first 4 months of this data to create a publication quality multi-line chart to help tell the visual story from the ride-sharing city type data.

The intended use of this data analysis and the related data visualization (chart) is to help the ride sharing company improve access to ride sharing services and to help determine affordability for underserved neighborhoods. 

This data analysis will be primarily focused on summarizing how the ride-share data differs across city types highlighting how the city type differences can be used by key decision-maker at the ride-sharing company.

### Objective 1: Summary of city type data for ride sharing
1. Calculate the total number of rides for each city type
2. Calculate total number of drivers for each city type
3. Calculate sum of the fares for each city type 
4. Calculate the average fare per ride for each city type is calculated
5. Calculate the average fare per driver for each city type 
6. Create summary DataFrame 
7. Format summary DataFrame

### Objective 2: Matplotlib multi-line change data visualization of total fare for each city type 
1. Create a pivot table using pandas pivot() 
2. Resample the pivot table data using Pandas resample() to get a better data set for the data visualization. (chart)
3. Create a multiple-line chart in Matplotlib that shows the total fares for each week by city type
4. Format the chart to be sized,styled and labeled improving usability and comprehension of the data presented

### Objective 3: Written report of ride-sharing city type data exploration 
A written report of this ride-sharing data analysis and data visualization work is included in this README.

### Resources
- Software: Python 3.6.1, Jupyter Notebook, Pandas, Matplotlib
## Analysis Results for Ride Share Data
1. Total rides for each city type:
   * Rural total rides = 125
   * Suburban total rides = 625
   * Urban total rides = 1,625
2. Total drivers for each city type:
   * Rural total drivers = 78
   * Suburban total drivers = 490
   * Urban total drivers = 2,405
3. Total fares for each city type:
   * Rural total fares = $4,327.93
   * Suburban total fares = $19,356.33
   * Urban total fares = $39,854.38  
4. Average fare per ride for each city type:
   * Rural average fare per ride = $34.62
   * Suburban average fare per ride = $39.50
   * Urban average fare per ride = $16.57
5. Average fare per driver for each city type 
   * Rural average fare per ride = $34.62
   * Suburban average fare per ride = $39.50
   * Urban average fare per ride = $16.57

A summary visualization of these result is shown here:

![ride-share data summary image](/Resources/pyber_summary_dataframe.png)

### Pivot table
The pivot table shows fares by date by city type and shows that on many dates there were no fares in the rural and suburan city types

![ride-share pivot table image](/Resources/pivot_table.png)

### Resampling
The resampling of the fares by date by city type to look at the data by week allows for seeing the trends for each ctiy more clearly as well as help provide a cleaner comparison fo the fares across the city types
![ride-share pivot table image](/Resources/resampling.png)

### Multiple-line chart

![ride-share data summary image](/Resources/fares_by_city_type_by_wk_mth_multi_line_chart.png)

### Differences in data among the different city types
General differences amonng the city types include
## Ride Share Data Visualization Summary and Proposed Recommendations
1. The pivot table show that on many days there were no Increasing the number of drivers in rural and suburban city types could make rides in these areas more accesible and affordable.
2. Giving rides in rural and sububuran areas could be more profitable for a driver than in Urban areas if the driver is willing take on giving more rides because the fares per driver are higher. 
3. Urban drivers could look at picking up near by Suburan rides to improve their usage rates. Surburban drivers could do the same with near by rural areas. Slight expansion of service areas out from urban to suburban and from surburban to rural could be good for drivers, rider access, and the company profits.

### References:
* Matplotlib documentation https://matplotlib.org/3.1.0/index.html
* Matplotlib backends https://matplotlib.org/3.1.1/api/matplotlib_configuration_api.html
* Matplotlib.plyplot.plot https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.pyplot.plot.html
* Matplotlib Pyploy API https://matplotlib.org/3.1.0/api/index.html#the-pyplot-api
* Anatomy of a Matplotlib chart https://matplotlib.org/tutorials/introductory/usage.html#parts-of-a-figure
* Matplotlib.axes.Axes.plot https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.axes.Axes.plot.html
* Matplotlib Axes class https://matplotlib.org/3.1.0/api/axes_api.html
* Matplotlib - creating a bar chart using the MATLAB method https://matplotlib.org/api/_as_gen/matplotlib.pyplot.bar.html#matplotlib.pyplot.bar
* Matplotlib - creating a horizontal bar chart uwing MATLAB method https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.pyplot.barh.html#matplotlib.pyplot.barh
* Matplotlib - creating bar charts using the object-oriented interface https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.axes.Axes.bar.html
* Matplotlib matplotlib.plyplt.scatter https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.scatter.html#matplotlib.pyplot.scatter
* Matplotlib simple scatter plot https://matplotlib.org/3.1.1/gallery/shapes_and_collections/scatter.html#sphx-glr-gallery-shapes-and-collections-scatter-py
* Matplotlib list comprehension https://docs.python.org/3.7/tutorial/datastructures.html#list-comprehensions
* Matplotlib list of named colors https://matplotlib.org/3.1.1/gallery/color/named_colors.html
* Matplotlib matplotlib.axes.Axes.scatter https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.axes.Axes.scatter.html
* Matplotlib scatter charts with a legend https://matplotlib.org/3.1.0/gallery/lines_bars_and_markers/scatter_with_legend.html#sphx-glr-gallery-lines-bars-and-markers-scatter-with-legend-py
* Matplotlib - creating a pie chart using MATLAB method https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.pie.html#matplotlib.pyplot.scatter
* Matplotlib - creating a pie chart using the object-oriented interface method https://matplotlib.org/3.1.0/api/_as_gen/matplotlib.axes.Axes.pie.html
* Matplotlib matplotlib.pyplot.errorbar https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.errorbar.html
* Matplotlib axes.Axes.errorbar https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.axes.Axes.errorbar.html
* Matplotlib  - major and minor ticks https://matplotlib.org/3.1.0/gallery/ticks_and_spines/major_minor_demo.html
* Pandas visualization https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html
* Git Hub README references https://github.com/inessadl/readme
* Matplotlib Markers https://www.w3schools.com/python/matplotlib_markers.asp
* Plotting with a transparent marker but non-transparent edge https://stackoverflow.com/questions/23596575/plotting-with-a-transparent-marker-but-non-transparent-edge
* matplotlib.markers.MarkerStyle https://matplotlib.org/stable/api/_as_gen/matplotlib.markers.MarkerStyle.html#matplotlib.markers.MarkerStyle
* Visualization with Matplotlib https://www.oreilly.com/library/view/python-data-science/9781491912126/ch04.html
* Determine matplotlib axis size in pixels https://stackoverflow.com/questions/19306510/determine-matplotlib-axis-size-in-pixels
* Python matplotlib clockwise pie charts https://stackoverflow.com/questions/48647268/python-matplotlib-clockwise-pie-charts
* matplotlib.axes.Axes.pie https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.axes.Axes.pie.html
* Python matplotlib clockwise pie charts https://stackoverflow.com/questions/48647268/python-matplotlib-clockwise-pie-charts
* Change the size of figures drawn with Matplotlib https://stackoverflow.com/questions/332289/how-do-you-change-the-size-of-figures-drawn-with-matplotlib
* Pandas documentation on visualization https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html
* Matplotlib style sheets https://matplotlib.org/stable/gallery/style_sheets/style_sheets_reference.html
* Matplotlib matplotlib.pyplot.legend https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.legend.html
* Matplotlib matplotlib.axes.Axes.legend https://matplotlib.org/2.0.0/api/_as_gen/matplotlib.axes.Axes.legend.html
* Matplotlib matplotlib.pyplot.text https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.text.html
* Mean, median, mode definitons https://www.cuemath.com/data/mean-median-mode/
* Matplotlib statistics visualizations https://matplotlib.org/3.1.1/gallery/index.html#statistics
* Matplotlib box plots https://matplotlib.org/examples/statistics/boxplot_demo.html
* Matplotlib - customizing Matplotlib with style sheets and rcParams

# Real Estate Investment Analysis


This program uses PropTech to build a program that offer an instant, one-click service for people to buy properties and then rent them. The program uses aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

----

## Technologies
This application is written in Jupyter Lab Notebook in the Python programming language. The Python libraries, tools, and modules used in this application are Pandas, hvPlot, and Path. Documentation shown below:

[Pandas](https://pandas.pydata.org/docs/index.html), [hvPlot](https://hvplot.holoviz.org/), [pathlib](https://docs.python.org/3/library/pathlib.html)

----

## Installation Guide
This program uses the Pandas library. If the user is not already running an environment that includes Pandas, then they will need to intall the library. Instructions shown in the installation guide --> [Pandas Installation Guide](https://pandas.pydata.org/docs/getting_started/install.html)

----

## Usage
For the program to run correctly, the user must make sure that all libraries and modules are correctly imported in the beginning of the code. This looks like:

    import pandas as pd
    
    import hvplot.pandas

    from pathlib import Path

The user must also make sure that their references to the San Francisco Housing data (sfo_neighborhoods_census_data.csv) reflects the correct location in their directory.

**The program is comprised of 4 parts:**

1. Calculate and plot the housing units per year.

In this section, the program will use numerical and visual aggregation to calculate the number of housing units per year. The program will then visualize the results as a bar chart so that the user can analyze the trend in housing units.

2. Calculate and plot the average prices per square foot.

In this section, the program will use numerical and visual aggregation to calculate the average prices per square foot. The program will then visualize the results as a line plot so that the user can analyze the data.

3. Compare the average prices by neighborhood.

In this section, the program uses interactive visualizations and widgets to explore the average sale price per square foot by neighborhood. The user will be able to toggle through neighborhood names to see the respective data in the line plot and analyze the data.

4. Build an interactive neighborhood map.

In this section, the program will explore geospatial relationships in the data by using interactive visualizations with hvPlot and GeoViews. The program will plot a map that the user can interact with to compare data from different neighborhoods. 

----

## Contributors

Arlie Jones

[E-mail](arliejones98@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/arlie-jones-020092159/)

----

## License

None
# Coursera:  Applied Plotting, Charting & Data Representation in Python

## Certificate: https://www.coursera.org/account/accomplishments/verify/DQ99M2WR99GK

This repository is mainly for projects I have done under a course of Coursera.

This course introduces the visualization basics, with a focus on reporting and charting using the matplotlib library. The course focuses on the technology used to make visualizations in python, matplotlib, and introduce users to best practices when creating basic charts and how to realize design decisions in the framework. There are also have a tutorial of functionality available in matplotlib, and demonstrate a variety of basic statistical charts helping learners to identify when a particular method is good for a particular problem. 

## Week 1: Principles of Information Visualization
Content: getting an introduction to principles of information visualization and some tools for thinking about design and graphical heuristics for thinking about creating effective visualizations

## Week 2: Basic Charting
### Project: 
An NOAA dataset has been stored in the file data/C2A2_data/BinnedCsvs_d400/fb441e62df2d58994928907a91895ec62c2c42e6cd075c2700843b89.csv. This is the dataset to use for this assignment. Note: The data for this assignment comes from a subset of The National Centers for Environmental Information (NCEI) Daily Global Historical Climatology Network (GHCN-Daily). The GHCN-Daily is comprised of daily climate records from thousands of land surface stations across the globe.
For this assignment, you must:

- Read the documentation and familiarize yourself with the dataset, then write some python code which returns a line graph of the record high and record low temperatures by day of the year over the period 2005-2014. The area between the record high and record low temperatures for each day should be shaded.
- Overlay a scatter of the 2015 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2015.
- Watch out for leap days (i.e. February 29th), it is reasonable to remove these points from the dataset for the purpose of this visualization.
Make the visual nice! Leverage principles from the first module in this course when developing your solution. Consider issues such as legends, labels, and chart junk.

## Week 3: Charting Fundamentals
### Project: 
In this paper the authors describe the challenges users face when trying to make judgements about probabilistic data generated through samples. As an example, they look at a bar chart of four years of data (replicated below in Figure 1). Each year has a y-axis value, which is derived from a sample of a larger dataset. For instance, the first value might be the number votes in a given district or riding for 1992, with the average being around 33,000. On top of this is plotted the 95% confidence interval for the mean (see the boxplot lectures for more information, and the yerr parameter of barcharts).

Easiest option: Implement the bar coloring as described above - a color scale with only three colors, (e.g. blue, white, and red). Assume the user provides the y axis value of interest as a parameter or variable.

Harder option: Implement the bar coloring as described in the paper, where the color of the bar is actually based on the amount of data covered (e.g. a gradient ranging from dark blue for the distribution being certainly below this y-axis, to white if the value is certainly contained, to dark red if the value is certainly not contained as the distribution is above the axis).

Even Harder option: Add interactivity to the above, which allows the user to click on the y axis to set the value of interest. The bar colors should change with respect to what value the user has selected.

Hardest option: Allow the user to interactively set a range of y values they are interested in, and recolor based on this (e.g. a y-axis band, see the paper for more details).

## Week 4: Applied Visualizations
Content: 
- Use at least two publicly accessible datasets from the same region that are consistent across a meaningful dimension. 
- State a research question that can be answered using these data sets and then create a visual using matplotlib that addresses your stated research question. 
- justify how your visual addresses your research question.


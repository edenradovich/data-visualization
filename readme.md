# Project: Flights in the United States
## by Eden Radovich

## Table of Contents
<ul>
<li><a href="#getting-started">Getting Started</a></li>
<li><a href="#intro">Introduction</a></li>
<li><a href="#summary">Summary of Findings</a></li>
<li><a href="#insights">Key Insights</a></li>
</ul>

<a id='getting-started'></a>

## Getting Started

This project requires Python and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](https://jupyter.org/).

If you do not have Python installed yet, install the [Anaconda](https://www.anaconda.com/download/#macos) distribution of Python, which already has the above packages and more included.

### Run
In a terminal or command window, run the following command:

    jupyter notebook
    
This will open the Jupyter Notebook software in your browser and you can navigate to the directory where the file is.

<a id='intro'></a>

## Introduction

The dataset contains over 21 million flights in the United States from the years 2006 to 2008 with information about arrival and departure times, airlines, cities, etc.

<a id='summary'></a>
## Summary of Findings

My findings illustrate that there are seasonal and weekend affects on delays. June and December experienced the highest delays across months. Additionally, Friday experienced the highest delays. While the frequency of flights does not change based on seasonality or weekend travel, it would appear that more popular travel times affect flight delays.

<a id='insights'></a>
## Key Insights

In the presentation I focus on the top ten most frequent flight paths, overlaying with month and day of week using pointplots and slight dodging to show variability across months/days of week. I did not go into detail regarding airlines delays as I was more interested in whether geography played a part in delayed flights. While the most frequent flight path from 2006 to 2008 was Boston to LaGuardia, Las Vegas to  Los Angeles had the greatest variability in flight delays, with the highest delays occurring in December.

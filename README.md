# MTA_Analysis - Best Stations for Advertising

## Abstract

The goal of this project was to virtualize traffic information of different MTA
stations and give advertising suggestions. By analyzing the MTA dataset, I got
the traffic information of each station on weekdays and weekends, during each time
period. Based on the traffic information and each station's coordinate, I'm able
to virtualize the result for a more clear view and give suggestions.

## Design

Company A wants to put out ads in some MTA stations from September to December.
They're advatising their brand new gaming laptops and desktops. Gaming laptops
are mostly targeting college students since most of them like and have the time
to play games. Desktops are targeting employees especially around IT companies.
The goal of this project was to analyze MTA dataset to give advertising suggestions
to the company.

## Data

The MTA dataset I'm using contains 3099133 rows of data, which includes 344 stations
with their coordinates. I also generated a dataset of 6 universities and 5 companies
in New York City by myself, which includes their names and coordinates.

## Algorithms

1. Get dataset from MTA website.
2. Get rid of stations that aren't in the coordinate dataset.
3. Get each station's daily entries and exits for comparison.
4. Separate them into to categories: weekdays and weekends
5. Get top 5 stations for weekdays and weekends
6. Combine time into time periods and generate hourly entries and exits for each station.
7. Generate graphs and maps

## Tools

* SQLite database system
* Pandas for data manipulation
* Matplotlib for plotting
* Folium for generating maps

## Communication

![](/Graph.jpg)

The project proposal is shown [here](/proposal.md).

Slides for this project is shown [here](/slides.pdf).

## How to run

Get MTA data by
```
python get_mta.py "(2109|2110|2111|2112)"
```

Run [final_project](/final_project.ipynb) in Jupyter Notebook

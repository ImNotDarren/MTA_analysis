# MTA_analysis - best stations for advertising

## Abstract

Company A wants to put out ads in some MTA stations from September to December.
They're advatising their brand new gaming laptops and desktops. Gaming laptops
are mostly targeting college students since most of them like and have the time
to play games. Desktops are targeting employees especially around IT companies.
The goal of this project was to analyze MTA dataset to give advertising suggestions
to the company.

I analyzed the MTA dataset and got the traffic information of each station on
weekdays and weekends, during each time period. Based on the traffic information
and each station's coordinate, I'm able to get my result.

## Design

## Data

The MTA dataset I'm using contains 3099133 rows of data, which includes 344 stations
with their coordinates. I also generated a dataset of 6 universities and 5 companies
in New York City by myself, which includes their names and coordinates.

## How to run

Get MTA data by
```
python get_mta.py "(2109|2110|2111|2112)"
```

Run [final_project](/final_project.ipynb) in Jupyter Notebook

## Other materials

Project proposal in [proposal.md](/proposal.md)

Results and other details in [slides.pdf](/slides.pdf)

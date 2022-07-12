# Project Proposal - Darren Liu
## Background Story

Company A wants to put out ads in some stations from September to December.
They're advatising their brand new gaming laptops and desktops. Gaming laptops
are mostly targeting college students since most of them like and have the time
to play games. Desktops are targeting employees especially around IT companies.

Company A needs the traffic information and location of each station from last
summer to decide where and when to put out those ads.

## Data discription

I'm planning on using the MTA dataset from September to December last year
and the location of each station.
I'll obtain the data from the MTA website.

Each row will represent the number of entries and exits in each unit during weekdays
and weekends, mornings, afternoons and nights. In this way I can get which station is
busy during weekdays in the morning and which is during weekends at night and so on
which can be used to determine which ad goes to which station. And I'll use the
location of each station to genurate the map.

## Tools
I'll be using SQLite database system and Python libraries like pandas for exploratory
data analysis and Python visualization libraries such as Folium, Matplotlib and Seaborn.

## MVP goal
My MVP goal would be visualizing the traffic information in different stations in
different time and give advertising suggestions based on it.
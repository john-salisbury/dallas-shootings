# Officer-Involved Shootings in Dallas, TX

An exploratory analysis of officer-involved shootings in Dallas, TX between 2003-2016 using SQL and Python.

***
### [View Interactive Project Summary](https://john-salisbury.github.io/dallas-shootings)
***

This analysis uses SQL and Python to examine officer-involved shootings in Dallas, TX between 2003-2016.

I came across [this interesting dataset](https://www.dallasopendata.com/Public-Safety/Dallas-Police-Officer-Involved-Shootings/4gmt-jyx2) while looking for public-facing SQLite databases to work with (credit to Stanford's [Public Affairs Data Journalism website](http://2016.padjo.org/tutorials/sqlite-data-starterpacks/) for a great list of public data!). It takes the form of a SQLite database with three tables that describe 14 years of shootings in which officers from the Dallas Police Department were involved. The data can also be found on the city of Dallas's [open data portal](https://www.dallasopendata.com/Public-Safety/Dallas-Police-Officer-Involved-Shootings/4gmt-jyx2).

In this analysis, I use SQL to explore and calculate summary statistics for the entire dataset. I then feed the data into Python's folium module to generate interactive maps that allow us to explore officer-involved shootings in a spatial context.

--

*Find the data for this project below:*
- [DPD Officer-Involved Shooting Data](https://www.dallasopendata.com/Public-Safety/Dallas-Police-Officer-Involved-Shootings/4gmt-jyx2)

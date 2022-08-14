# Real_Estate_Project

![Columbia Engineering.](images/Columbia.jpeg)

___
The project objective was to determine ideal cities to purchase investment properties considering a balance of rental income and mortgage debt. Additional analysis we did was to calcualte the percentage change in average rental price and property value since 2014, which was used to calculate the cumulative returns and visualize growth in each housing market. Further, we calculated the cash flow provided a national average mortgage rate of 4.87%. 

---

## Technologies

This project leverages python 3.7 with various Libraries and IDE:

* [Jupyterlab](http://justinbois.github.io/bootcamp/2020_fsri/lessons/l01_welcome.html#Jupyter) - An interactive development environment

* [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) - SQLAlchemy is a Python toolkit and an object relational mapper.

* [Voila](https://voila.readthedocs.io/en/stable/) - A Python library that allows one to convert a Jupyter Notebook into an interactive dashboard that allows you to share your work with others.

* [PyViz](https://pyviz.org/overviews/index.html) - a is a Python visualization package that provides a single platform for accessing multiple visualization libraries, including hvPlot and GeoViews.

* [hvPlot](https://hvplot.holoviz.org/user_guide/Plotting.html) -  a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data in various formats.

* [Plotly.express](https://plotly.com/python/plotly-express/) - a high level Python visualization library.

---

## Installation Guide

In order to run the application, one should first install SQLAlchemy and Voila.

* Install SQLAlchemy
![Install SQLAlchemy](images/Install%20SQLAlchemy.PNG)

* Install Voila
![Install Voila](images/Install%20Voila.PNG)

* Install PyViz
![Install PyViz](images/Installing%20PyViz.PNG)

* Loading all necessary libraries ![Install libraries](images/install_libraries.PNG)
---

## Usage
To use the analysis, clone the repository and run the four notebooks:

a) city_project.ipynb - this notebook contains the data prep that enabled the group to identify 10 cities of interest based on highest average rent prices as of June 2022. Furhter, it includes analysis of average rent price vs. mortgage debt over four separate time windows: June 2022, January 2020 - June 2022, January 2014 - December 2019, and January 2014 - June 2022. These time windows were chosen for a comparison of the renatl and housing markets before and after the recent Covid Pandemic. Additionally, it includes an interactive map of the 10 cities.

* The 10 selected cities on a map![Map](images/Map.png)
* Rental prices since for selected cities since June 2014![RentalPrices](images/Rent%20since%202014.png)
* Property Values for selected cities since January 2000![PropertyValues2000](images/Property%20Values%20Since%202000.png)
* Debt-to-Income ratio comparison for selected cities since 2014![DTI](images/DTI.png)

b) city_roc.ipynb - this notebook containd data prep to slice data into the same windows mentioned in a), and to calculate the rate of change, mortgage payments, and cash flows for each of the cities of interest.

* Percent Change in Rental Prices![Rent](images/Pct%20Change%20Rent.png)
* Percent Change in Property Values![PropertyValues](images/Pct%20Change%20Property%20Values.png)
* Cash Flow Analysis for each city![CashFlow](images/Cash_Flow.png)

c) city_returns_ranking.ipynb - this notebook contains data prep and the calculation of percentage change and cumulative returns on rental income and property value.

* Monthly Return of Rental Values since 2014![MonthlyRentalReturns](images/Monthlyreturn2014.png)
* Cumulative Growth in Rental Prices since 2014![CumulativeRent](images/Cumulativegrowthrent2014.png)

d) city_visualizations.ipynb - this notebook contains some data prep that enabled the group to create an animation of the changes in rent and property values since 2014.

* Changes in rental prices and property values since 2014 ![Animation](images/Changes%20in%20Rent%20and%20Property%20Values%20Since%202014.gif)

---

## Next Steps

Given the timeframe and the scope of this project, we were not ablet o incorporate everything we would have liked to. Following are some ideas we would incorporate given more time:

a) Monte Carlo Simulations to forecast prices & rent for selected cities as well as all cities in data set.

b) Include additional factors for analysis such as taxes (property/income), insurance, demographics.

c) Further explore the effect Covid had on housing markets.

---


## Contributors

This project included a group effort from Sheng Gao, Yuvraj Kabra, Nirav Metha, and Franco Thomas.

We would like to thank you for reading this file and gowing through our project.

---

## License

MIT
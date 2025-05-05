# energy_consumption_analysis

This project analyzes the energy consumption of groups of customers, using data collected from an energy company for a year. The goal is to process the data, using Apache Spark (PySpark) techniques to:
- clean and reorganize the data
- fill in missing values
- calculate the energy bill (and comparing it with other ones)

The objectives for this project are:
- use data transformation and aggregations to solve the problems
- find a pattern for some columns (e.g. regions may be shown as "continent/city", some other columns have only 2-3 values)
- extract features from a single column and put each of them into new columns
- predict unusual energy consumption with various techniques, via aggregations or machine learning techniques (KMeans, isolation forests)
    - ML algorithms can be used also for completing NULL values
- associate these two datasets (`raw_time_series` and `customer_tariff`) and calculate the final prices by day / week / month / year

The project's requirements can be found on [this PDF](https://github.com/livonschistrate/energy_consumption_analysis/blob/main/Project.pdf) (in Romanian)

This project was completed as part of the *Hands On Advanced Analytics with Apache Spark* course, by [E.ON Software Development](https://www.eon-romania.ro/ro/cariera/eon-software-development.html), at [FIIPractic](https://fiipractic.asii.ro/).
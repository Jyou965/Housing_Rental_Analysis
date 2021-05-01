# Housing_Rental_Analysis

This application uses data visualization tools to show relationships among real estate data and identify housing investment opportunities.

---

## Libraries and Dependancies

This application leverages python 3.7 with the following packages:

* [os](https://docs.python.org/3/library/os.html) - provides a portable way of using operating system dependent functionality.

* [pandas](https://pandas.pydata.org/docs/) - an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [plotly.express.scatter_mapbox](https://plotly.github.io/plotly.py-docs/generated/plotly.express.scatter_mapbox.html) - a powerful visualization library that can produce advanced charts and interactive visualizations.

* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - provides a high-level plotting API built on HoloViews and Bokeh that provides a general and consistent API for plotting data in all the abovementioned formats.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - for utilizing filesystem paths with semantics appropriate for different operating systems.

* [dotenv](https://pypi.org/project/python-dotenv/) - reads key-value pairs from a .env file and can set them as environment variables.

---

## Usage

This application uses visualization tools to display real estate market data in San Francisco from 2010 to 2016 in the following steps:

1. Display the housing units per year in San Francisco during the period.

2. Compare the overall San Francisco growth rate of sales price per squart foot with that of gross rent to observe the trend of rent growth far outpacing sales price growth throughout the period. Even when sales price dipped in 2011, rent still rose.

3. Compare the sales price growth vs. rent growth by neighborhood and the same trend of rent growth outpacing sales price growth applies to all neighborhoods.

4. Using an interactive map to identify the neighborhoods with the highest gross rent and with the highest sales price per square foot.

5. Identify the neighborhood that presents the most attractive rental yield as a buy-and-rent strategy.


With the visualization tools, the user can digest the data intuitively and identify opportunities with ease.

---

## Contributors

Jackie You with the support of FinTech Boot Camp Staff

---

## License

Berkeley
<img src="https://raw.githubusercontent.com/jeremielamboley/global-passport-index/master/source_files/passport-illustration.jpg" width="350">

# An improved ranking of the world’s passports with Python Pandas and Plotly visualizations

In this project, we have combined a passport relationship table with countries statistics in order to challenge existing passport rankings and propose a alternative rankings. We have then used plot.ly to make the data interactive and visually appealing.

## Publication

The data gathered have been used in an article published on Medium, which detail the method and include the visualizations:
https://medium.com/@jeremielamboley/visualization-passports-index-python-pandas-plotly-943f501b9d67

## Main features

* gather data to replicate the traditional passports rankings
* add external countries statistics from reputable sources
* propose a new and improved ranking method

## Credits

Special thanks to:
* Guy Freeman (https://github.com/slygent) for the scrapy script.
* Ahmed Benjelloun (https://github.com/abenjelloun1) for his feedback and help with the code of the visualizations.
* Xavier Mathieu (https://github.com/bluexm) for his precious mentorship and help to make this project more digestible and engaging.

## Data sources 

* Country codes list: https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes, scrapped by Juanu https://www.kaggle.com/juanumusic/countries-iso-codes
* Countries data: The United Nations Statistics Division http://data.un.org/
* Unesco World Heritage List http://whc.unesco.org/en/syndication

## Software and Libraries

This project uses the following software and Python libraries:

- [Python](https://www.python.org/download/releases/3.0/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scrapy](https://scrapy.org/)
- [plotly](https://plot.ly/python/getting-started/)
- [ipywidgets](https://github.com/jupyter-widgets/ipywidgets#install)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has most of the above packages (except scrapy) and more included. 

## Developing

Any database with a list of country in a ISO 3166-1 format can be added to enrich the ranking.

If you want to develop the project further:

```shell
git clone https://github.com/jeremielamboley/global-passport-index.git
cd global-passport-index/
```

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Links

- Repository: https://github.com/jeremielamboley/global-passport-index
- Issue tracker: https://github.com/jeremielamboley/global-passport-index/issues
  - In case of sensitive bugs like security vulnerabilities, please contact jeremie@lamboley.pro directly instead of using issue tracker. We value your effort to improve the security and privacy of this project!
- Related projects:
  - My main gitHub page: https://github.com/jeremielamboley

## Licensing

The code in this project is licensed under Apache License 2.0.

<img src="https://raw.githubusercontent.com/jeremielamboley/world-passport-power-rank-enriched/master/source_files/passport-illustration.jpg" width="350">

# World passport power rank, enriched edition
> Go beyond the traditional passport ranking and discover how much of the world surface/GDP/population you can explore, visa-free!

Using a scraped copy of the Henley passport ranking, I have combined the traditional passport rank with United Nations Statistics Division data in order to get a more realistic view of how powerful world passports are.

Not all countries are equal in terms of surface, population, GDP.. so why passport ranks should take into account only a countries sums without weighting them ?

## Features

* Improved passport ranking with each country weighted
* Correlations between rank, region and development stages
* Biggest win and drops compare to the traditional passport indexes

## Interesting findings

A detailed blogpost will be published on Medium shortly.

## Credits

Special thanks to:
* Guy Freeman (https://github.com/slygent) for the scrapy script of www.henleypassportindex.com/
* Ahmed Benjelloun (https://github.com/abenjelloun1) for his feedback and help with the data visualizations. 

## Data sources 

* Visa free list: Henley www.henleypassportindex.com/ (199 different passports and 227 different travel destinations as of January 2019), data provided by the International Air Transport Authority (IATA)
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
git clone https://github.com/jeremielamboley/world-passport-power-rank-enriched.git
cd world-passport-power-rank-enriched/
packagemanager install
```

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Links

- Repository: https://github.com/jeremielamboley/world-passport-power-rank-enriched
- Issue tracker: https://github.com/jeremielamboley/world-passport-power-rank-enriched/issues
  - In case of sensitive bugs like security vulnerabilities, please contact jeremie@lamboley.pro directly instead of using issue tracker. We value your effort to improve the security and privacy of this project!
- Related projects:
  - My main gitHub page: https://github.com/jeremielamboley

## Licensing

The code in this project is licensed under Apache License 2.0.

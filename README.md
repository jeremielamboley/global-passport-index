<img src="https://raw.githubusercontent.com/jeremielamboley/world-passport-power-rank-enriched/master/passport-illustration.jpg" width="350">

# World passport power rank, enriched edition
> Go beyond the traditional passport ranking and discover how much of the world surface/GDP/population you can explore, visa-free!

Using a scraped copy of the Henley passport ranking, I have combined the traditional passport rank with United Nations Statistics Division data in order to get a more realistic view of how powerful world passports are.

Not all countries are equal in terms of surface, population, GDP.. so why passport ranks should take into account only a countries sums without weighting them ?

## Features

* a new (hopefully better!) passport ranking
* highlight the biggest win and drops compare to the traditional ranking system

## Interesting findings (so far)

Expected end of January 2019

## Credits

Special thanks to:
* Guy Freeman for the scrapy script of www.henleypassportindex.com/ https://github.com/slygent

## Data sources 

* Visa free list: Henley www.henleypassportindex.com/ (199 different passports and 227 different travel destinations as of January 2019), data provided by the International Air Transport Authority (IATA)
* Country codes list: https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes, scrapped by Juanu https://www.kaggle.com/juanumusic/countries-iso-codes
* Countries data: The United Nations Statistics Division http://data.un.org/
* Unesco World Heritage List http://whc.unesco.org/en/syndication

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

Even though this information can be found inside the project on machine-readable
format like in a .json file, it's good to include a summary of most useful
links to humans using your project. You can include links like:

- Repository: https://github.com/jeremielamboley/world-passport-power-rank-enriched
- Issue tracker: https://github.com/jeremielamboley/world-passport-power-rank-enriched/issues
  - In case of sensitive bugs like security vulnerabilities, please contact jeremie@lamboley.pro directly instead of using issue tracker. We value your effort to improve the security and privacy of this project!
- Related projects:
  - My main gitHub page: https://github.com/jeremielamboley

## Licensing

The code in this project is licensed under Apache License 2.0.

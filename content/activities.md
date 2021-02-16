---
 layout: default
 title: What is web scraping?
 parent: Outline
 nav_order: 1
---

## Data Miner Activity

If you haven't already, install <a href="https://chrome.google.com/webstore/detail/data-scraper-easy-web-scr/nndknepjnldbdbepjfgmncbggmopgden">Data Miner plugin for Chrome</a>.

1. Working from the "Recipes" tab, go to [Google Scholar](https://scholar.google.com), do a search, and save the results of your search with a "Google Scholar" Recipe.

2. Build a new recipe to scrape one of the following:
- names and email addresses from the [UBC directory](https://directory.ubc.ca/index.cfm)
- search results from [UBC Library](https://library.ubc.ca)
- *any other page you like!*

## Scripting Activities

If you are using [UBC Sygyzy](https://ubc.syzygy.ca/) you can generally skip tutorial instructions about local environment setup (eg. installing Python or R). Begin by from the point of importing libraries and do this directly into Sygyzy.

### Python tutorials
* [Hitchhikers Guide to Python" html scraping tutorial (uses Python 2.x)](https://docs.python-guide.org/scenarios/scrape/)
  * To update to Python3, change
    ```python
    print 'Buyers: ', buyers
    print 'Prices: ', prices
    ```
    to
    ```python
    print (buyers)
    print (prices)
    ```
  * if lxml is not found in your environment run this first:
  '''python
  pip install lxml
  '''
* [Data Camp tutorial](https://www.datacamp.com/community/tutorials/web-scraping-using-python)
* [RealPython tutorial](https://realpython.com/python-web-scraping-practical-introduction/)

### R tutorials (all use the rvest library)
* [Data Camp tutorial](https://www.datacamp.com/community/tutorials/r-web-scraping-rvest)
* [DataQuest tutorial](https://www.dataquest.io/blog/web-scraping-in-r-rvest/)
* [Free Code Camp tutorial](https://www.freecodecamp.org/news/an-introduction-to-web-scraping-using-r-40284110c848/)
* [Beginners guide to web scraping in R](https://www.analyticsvidhya.com/blog/2017/03/beginners-guide-on-web-scraping-in-r-using-rvest-with-hands-on-knowledge/)

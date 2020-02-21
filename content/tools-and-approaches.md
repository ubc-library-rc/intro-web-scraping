---
 layout: default
 title: Tools and approaches
 parent: Outline
 nav_order: 3
---
# Tools and approaches

## Working with a visual tools

There are many reasons that you might want to skip the scripting process and want to use a pre-built tool. Modern visual scraping tools are robust, designed to avoid getting blocked by the requirements of a specific website, and generally easy to set up.

For this workshop we will primarily be talking about one tool that represents a good example of a visual web scraper:

<a href="https://data-miner.io/">Dataminer</a>(and other plugins)

## Scripting

For this workshop we are focusing on Python based tools. Python is a common programming language and has a number of tools inside of it that help with web scraping. It is also relatively friendly for beginners to understand. There are many other tools for web scraping in other languages.

Generally tools can be divided into two general categories:
* Tools that get information from the web
* Tools that parse the information you getting

In Python sets of related tools get organized into "Libraries" (eg. tools for both scraping and parsing in one) and "Frameworks" which offer more structure for the application of a certain set of tools than a library would.

The most common Python based tools for web scraping that you are likely to run into are:
* <a href="https://requests.readthedocs.io/en/master/">requests</a>
  * a library for getting data from the web.
  * tools to communicate over HTTP.
* <a href="https://docs.python.org/2/library/urllib.html">urllib</a>
  * tools to communicate over HTTP.
  * best for smaller amounts of data, very similar to requests.
* <a href="https://lxml.de/">lxml<a/>
  * a set of tools for parsing html and xml.
* <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">Beautiful Soup</a>
  * a slightly larger set of tools for parsing html and xml.
* <a href="https://scrapy.org/">Scrapy</a>
  * a framework for web crawling and web scraping. For getting small and large amounts of data from the web and automating requests to happen repeatedly or over time.
  * A parser which processes html or xml by standardizing it. Beautiful soup can troubleshoot structural problems in the output of your scrape such missing or open html tags.

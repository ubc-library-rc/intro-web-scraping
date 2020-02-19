---
 layout: default
 title: Tools and approaches
 parent: Outline
 nav_order: 2
---
# Tools and approaches

Python is a common programming language and has a number of tools inside of it that help with web scraping.

The most common Python based tools for web scraping that you are likely to run into are:
* requests
 * a library for getting small snippets of data from the web.
 * tools to communicate over HTTP
* Scrapy
  * a framework for web crawling and web scraping. For getting small and large amounts of data from the web and automating requests to happen repeatedly or over time.
  * A parser which processes html or xml by standardizing it. Beautiful soup can troubleshoot structural problems in the output of your scrape such missing or open html tags.
* urllib
  * tools to communicate over HTTP
  * best for smaller amounts of data, very similar to requests

Library vs. Framework

Dataminer (and other plugins)

# Understanding a website

HTTPS - hypertext transfer protocol secure

A web browser works by understanding HTTP/HTTPS and knowing how to represent it.

GET - most common http method, retrieve a resource from server. This is what comes into play when you to go a url with a web browser.
POST - send data to server
HEAD - just get the head of a resource without the full content (great for figuring out what it is)

HTML - hypertext markup language

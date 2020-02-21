---
 layout: default
 title: Understanding a website
 parent: Outline
 nav_order: 2
---
# Understanding a website

Website content is represented using HTML, or Hypertext Markup Language. Web servers make this HTML content avaialble browsers using a communication method called HTTP (Hypertext Transfer Protocol).  A web browser works by using HTTP to access documents in HTML format, then rendering them in the the browser window.

Web scraping tools use the HTML structure of a website to navigate the page and identify the content to scrape. Sites whose underlying structure is well organized and descriptive are usually easier to scrape. Effective use of web scraping tools requires at least a basic understanding of how web pages are structured and how their content is served.

<a href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics">Anatomy of an HTML element.</a>

## Using Browser "Inspect" tools

Modern browsers have built-in "inspect" tools that reveal the underlying HTML structure of a web page. In Chrome and Firefox, right-clicking on part of the page and selecting *Inspect* (Chrome) or *Inspect element* (Firefox) will show where the selected element appears in the the page HTML.

This screenshot shows the *Inspect* tool applied to a simple website accessed using Chrome: http://econpy.pythonanywhere.com/ex/001.html.  The website is a simple list of buyer names and item prices.

![Inspect tool example](media/inspect_tool.jpg)

In a simple site it is easy to see the correlation between the content and the HTML elements. You can expand the HTML elements in the inspection window to reveal other content.

## Scraping examples

To help illustrate how scrapers use HTML to identify content we will use the Data Miner extension for Chrome.

- Scraping example 1: search results from [Google Scholar](https://scholar.google.com)
- Scraping example 2: Member of Parliament [addresses](https://www.ourcommons.ca/Members/en/search)


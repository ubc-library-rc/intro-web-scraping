---
 layout: default
 title: Understanding website structure
 parent: Outline
 nav_order: 2
---
# Understanding website structure

<em><a href="../slides/website-structure.html" target="_blank">View slides</a> for this section</em>

Website content is usually represented using HTML, or **H**yper**t**ext **M**arkup **L**anguage. Web servers make HTML content available to browsers using a data transfer protocol called HTTP (**H**yper**t**ext **T**ransfer **P**rotocol). Two of the most common HTTP request methods are *get* (to request data from a server) and *post* (to send data to a server).

Web scraping tools use a website's HTML structure to navigate the page and identify the content to scrape. Effective use of web scraping tools requires a basic understanding of how web pages are structured. Sites whose underlying structure is well organized and descriptive are usually easier to scrape.

<a href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics" target="_blank">Anatomy of an HTML element.</a>


## Using Browser "Inspect" tools

Most browsers have built-in "inspect" tools that allow you to explore the HTML structure of a web page. Right-click any part of a page and select *Inspect* or *Inspect element* to open a panel showing how the selected content is represented in the HTML.

<p>In Safari and Microsoft Edge <strong>inspect element</strong> is not enabled by default.<br>* To enable in <strong>Safari</strong> go to Preferences -> Advanced and enable <i>Show Developer menu in menu bar</i>. <br> * To enable in <strong>Microsoft Edge</strong> press F12</p>
{: .note}

This screenshot below shows the *Inspect* tool applied to a web page accessed with Chrome: <a href="http://econpy.pythonanywhere.com/ex/001.html" target="_blank">http://econpy.pythonanywhere.com/ex/001.html</a>. The page is a list of buyer names and item prices.

![Inspect tool example](media/inspect_tool.png)

In a simple site like this it is easy to see the correlation between displayed content and HTML elements. You can expand the HTML elements in the inspection window to reveal other content and hover over elements to highlight the corresponding section in the web page.

Web scrapers navigate the HTML structure using *XPath*, a language that identifies and selects content *nodes* on the site. In the example above all buyer names are contained in <div> elements like this

```
<div title="buyer-name">Moe Dess</div>
```

The XPath expression that identifies all "buyer-name" nodes on the page is

```
//div[@title="buyer-name"]
```


## Scraping examples

To help illustrate how scrapers use HTML to identify content we will use the Data Miner extension for Chrome.

The Data Miner extension is an accessible way to introduce web scraping concepts. It's a helpful learning tool but more sophisticated scraping is usually accomplished with scripts (e.g. Python), especially in research were reproducibility is important.

- Scraping example 1: search results from <a href="https://scholar.google.com" target="_blank">Google Scholar</a>.


- Scraping example 2: Member of Parliament <a href="https://www.ourcommons.ca/members/en/addresses" target="_blank">addresses</a>.


## Data Miner Activity

If you haven't already, install <a href="https://chrome.google.com/webstore/detail/data-scraper-easy-web-scr/nndknepjnldbdbepjfgmncbggmopgden">Data Miner plugin for Chrome</a>.

1. Working from the "Recipes" tab, go to [Google Scholar](https://scholar.google.com), do a search, and save the results of your search with a "Google Scholar" Recipe.

2. Build a new recipe to scrape one of the following:
- names and email addresses from the [UBC directory](https://directory.ubc.ca/index.cfm)
- search results from [UBC Library](https://library.ubc.ca)
- *any other page you like!*

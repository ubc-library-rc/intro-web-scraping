---
 layout: default
 title: Activities
 parent: Outline
 nav_order: 4
---

## Google colab Activity
This example is adapted from the <a href="https://docs.python-guide.org/scenarios/scrape/">"Hitchhikers Guide to Python" html scraping tutorial</a>.

1. Open a Google Colab notebook here: [https://colab.research.google.com/](https://colab.research.google.com/).  Login with a Google account, then select "_File_ -> _New notebook_" for a basic coding environment.

2. Add a code cell by clicking _+ Code_. Copy the script below into the code cell, then click the _play_ icon to run the code. 

Input
{: .label .label-green }
~~~python
from lxml import html
import requests
page = requests.get('http://econpy.pythonanywhere.com/ex/001.html')
tree = html.fromstring(page.content)
#This will create a list of buyers:
buyers = tree.xpath('//div[@title="buyer-name"]/text()')
#This will create a list of prices
prices = tree.xpath('//span[@class="item-price"]/text()')
print (buyers)
print (prices)
~~~

You should see the following output.

Output
{: .label .label-yellow }
~~~python
['Carson Busses', 'Earl E. Byrd', 'Patty Cakes', 'Derri Anne Connecticut', 'Moe Dess', 'Leda Doggslife', 'Dan Druff', 'Al Fresco', 'Ido Hoe', 'Howie Kisses', 'Len Lease', 'Phil Meup', 'Ira Pent', 'Ben D. Rules', 'Ave Sectomy', 'Gary Shattire', 'Bobbi Soks', 'Sheila Takya', 'Rose Tattoo', 'Moe Tell']

['$29.95', '$8.37', '$15.26', '$19.25', '$19.25', '$13.99', '$31.57', '$8.49', '$14.47', '$15.86', '$11.11', '$15.98', '$16.27', '$7.50', '$50.85', '$14.26', '$5.68', '$15.00', '$114.07', '$10.09']
~~~

Explore the structure of the script reflected when we use the inspect function in a browser.
![Inspect element example for ](media/script-inspect-element-screenshot.png)

## Optional - Data Miner Activity

If you haven't already, install <a href="https://chrome.google.com/webstore/detail/data-scraper-easy-web-scr/nndknepjnldbdbepjfgmncbggmopgden">Data Miner plugin for Chrome</a>.

1. Working from the "Recipes" tab, go to [Google Scholar](https://scholar.google.com), do a search, and save the results of your search with a "Google Scholar" Recipe.

2. Build a new recipe to scrape one of the following:
- names and email addresses from the [UBC directory](https://directory.ubc.ca/index.cfm)
- search results from [UBC Library](https://library.ubc.ca)
- *any other page you like!*



---
 layout: default
 title: What is web scraping?
 parent: Outline
 nav_order: 1
---
# What is web scraping?

Web scraping is a technique for extracting information from websites. This can be done manually
but it is usually faster, more efficient and less error-prone to automate the task.

Web scraping allows you to acquire non-tabular or poorly structured data from websites and convert it
into a usable, structured format, such as a .csv file or spreadsheet.

There are a variety of ways to scrape a website to extract information for reuse. In its simplest form, this can be achieved by copying and pasting snippets from a web page, but this can be unpractical if there is a large amount of data to be extracted, or if it spread over a large number of pages. Instead, specialized tools and techniques can be used to automate this process, by defining what sites to visit, what information to look for, and whether data extraction should stop once the end of a page has been reached, or whether to follow hyperlinks and repeat the process recursively. Automating web scraping also allows to define whether the process should be run at regular intervals and capture changes in the data.

For example, online stores will often scour the publicly available pages of their competitors,
scrape item prices, and then use this information to adjust their own prices. Another common
practice is "contact scraping" in which personal information like email
addresses or phone numbers is collected for marketing purposes.

Web scraping is also increasingly being used by scholars to create data sets for
text mining projects; these might be collections of journal articles or digitised texts.


## Scraping vs crawling
It's helpful to differentiate between *web scraping* and *web crawling*.  Crawling is what search engines like Google do when mass-analysing the Web to build their indices. A *crawler* is a type of bot that accesses pages and follows any links they find, "crawling" through an entire website or group of sites. 

*Web scraping* is more targeted than crawling. A scraper identifies and extracts specific content from the pages it accesses. In practice crawlers and scrapers are sometimes used together but the examples in this workshop do not include crawlers.


## Is scraping the best option?

Scraping can automate repetitive data retrieval tasks but depending on the site there may be simpler ways to accomplish this. Choose the easiest tool for the job:

- Check whether or not you can easily copy and paste data from a site into Excel or Google Sheets. This might be quicker than scraping.
- Check whether the site provides an export feature with the data you need (e.g. for contact lists or search results).
- Check if the site or service provides an API to extract structured data. Depending on your comfort level with APIs this could be more efficient.


## Ethics and considerations

Just because something is online does not mean it is free to scrape. Sites may wish to control how the information they provide is accessed and used. Intensive web scraping can also put high demands on the website's server. Some sites may expressly forbid web scraping in the terms of use or include a *robots.txt* file that specifies how crawlers and scrapers may access the site.  

![robots.txt comic](media/robots.png)
Source: http://locomostrip.com/comic/179/

A few questions to consider when deciding whether web scraping is appropriate:

- *Am I allowed to take this data?* Check the website for terms of use that affect web scraping.
- *Are there restrictions on what I can do with this data?* Making a local copy of publicly available data is usually OK, but there may be limits on use and redistribution of the content. 
- *Am I overloading the website's servers?* Scraping practice should respect the website's access rules, often encoded in *robots.txt* files. Websites may also impose limits on how many pages users can visit within a certain time period. 


There are grey areas as scraping involves interacting with a website in a way that the site owner might not have intended. When in doubt get in touch with a librarian or contact UBC's [Copyright Office](https://copyright.ubc.ca/support/contact-us/).

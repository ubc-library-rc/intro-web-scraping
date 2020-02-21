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

Scraping is about more than just acquiring data: it can also help you archive data and track changes to data online.

It is closely related to the practice of
web _indexing_, which is what search engines like Google do when mass-analysing the Web to build
their indices. But contrary to _web indexing_, which typically parses the entire content of a web
page to make it searchable, _web scraping_ targets specific information on the pages visited.

For example, online stores will often scour the publicly available pages of their competitors,
scrape item prices, and then use this information to adjust their own prices. Another common
practice is "contact scraping" in which personal information like email
addresses or phone numbers is collected for marketing purposes.

Web scraping is also increasingly being used by scholars to create data sets for
text mining projects; these might be collections of journal articles or digitised texts.

Two approaches:
* Saving the guts of a website and then working on that output in order to clean it and make it useable
* Directly interacting with the website to get content out of it programmatically

In both cases you are essentially targeting html elements to get a certain type of information out of a website.

## Do you need to scrape?

Scraping is a way to automate repetitive data retrieval tasks. As useful as scraping is, there are often simpler ways to accomplish this. Choose the easiest tool for the job.

- Check whether or not you can easily copy and paste data from a site into Excel or Google Sheets. This might be quicker than scraping.
- Check whether the site provides an export feature (e.g. for contact lists or search results)
- Check if the site or service provides an API to extract structured data.


## Ethics and considerations

Just because something is online does not mean it is free to scrape. Web scraping can be resource intensive on the server providing the site, or sites may wish to control how the information they provide is used. Some sites may expressly forbid web scraping in the terms of use or configure their websites with a robots.txt file that attempts to block scraping.  Some questions to ask yourself before scraping:

- am I allowed to take this data?
- are there restrictions on what I can do with this data?
- am I overloading the website's servers?
- am I intentionally bypassing a site's attempt to avoid scraping?

There are grey areas -- when in doubt get in touch with a librarian or reach out directly to our Copyright office.

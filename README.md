# Scrapy platform

Powered by [Scrapy](https://github.com/scrapy/scrapy)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

The scrapy platform will extend the scrapy framework to a GUI form.
This platform will store a list of your spiders and the ability to check if they are still viable.
For example a website can change causing the webscraper in some cases to break.

the list will Also store the list of inputs the scrapy needs for example if a scrapy is used to scrap links for a search engine from a search phrase.

Scrapy inputs and putputs have the ability to be chained.

Another example would be a genric spider that looks for contact if from html.

All variables of a spider can be changed form the UI.
Createing a new spider
Streamline
If the website is rendered in javascript automically configure spider to send requests through splash
add xpaths and the name of the data they will return and type.
example list, string, number, link
Create A alogrithm to determine the most accruate xpath for data accross pages.

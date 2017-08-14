# README #

Scrapy crawler that collects auction events from

https://www.glenmarch.com/auctions/results/

### Dependencies ###

This crawler is tested to work under Python 2.7.

Required dependencies to make this package run are:

- python >= 2.7
- scrapy

You can install this dependent package with the following command:

pip install scrapy

### Execution ###

You can run this scrapy crawler typing:

scrapy crawl glenmarch -a id=NUMERICALIDHERE -o file.csv -t csv

The previous command will output to a .csv file

### Settings ###

This crawler is configured to cache pages for 24 hours. You can change
this behaviour by editing the 88 line in settings file:

glenmarch/settings.py

Or disable caching by adding a # in the start of the line.

### Contact ###

Author: Luis Torres

* luis.e.torreslopez [at] gmail.com
* github.com/letorresl

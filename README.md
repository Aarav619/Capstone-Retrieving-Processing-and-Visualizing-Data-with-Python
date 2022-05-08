# Retrieving-Processing-Visualizing-Data-with-Python

This course is part of the Python for Everybody Specialization | which, includes a series of applications to retrieve, process and visualize data using Python.

## References

-   [Coursera](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
-   [PageRank](./week%203/README.md)
-   [Analyzing email data](/week%204-6/README.md)

## Visualizing networks and interconnections

In this application, we will perform some of the functions of a search engine. We will first spider a small subset of the web and run a simplified version of the Google page rank algorithm to determine which pages are most highly connected, and then visualize the page rank and connectivity of our small corner of the web. We will use the D3 JavaScript visualization library [d3js](http://d3js.org/) to produce the visualization output.

You can download and extract this application from [here](www.py4e.com/code3/pagerank.zip).

### Description

-   Page Ranking: The first program ([spider.py](./week%203/spider.py)) program crawls a web site and pulls a series of pages into the database (spider.sqlite), recording the links between pages. You can restart the process at any time by removing the spider.sqlite file and re-running [spider.py](./week%203/spider.py).

### OUTPUT

<div align="center">
<img src="week 3/screenshot.png" alt="PageRank-Output" width="400" height="300">
</div>

---

## Visualizing mail data

In this section, we work with an application that is the most complex so far and pull down nearly a gigabyte of data and visualize it.
We will be using data from a free email list archiving service called [gmane](http://www.gmane.org). This service is very popular with open source projects because it provides a nice searchable archive of their email activity. They also have a very liberal policy regarding accessing their data through their API. They have no rate limits, but ask that you don’t overload their service and take only the data you need. You can read gmane’s terms and conditions at this page [gmane.org](http://www.gmane.org/export.php).

It is very important that you make use of the gmane.org data responsibly by adding delays to your access of their services and spreading long-running jobs over a longer period of time. Do not abuse this free service and ruin it for the rest of us.

### OUTPUT

<div align="center">
<img src="week 4-6/screenshot.png" alt="WordCloud-Output" width="400" height="300">
</div>

A Word Cloud from the Sakai Developer List
You can download this application from
[here](https://www.py4e.com/code3/gmane.zip).

> A second visualization is produced by [gline.py](/week%204-6/gline.py). It computes email participation by organizations over time. Its output is written to gline.js which is visualized using [gline.htm.](/week%204-6/gline.htm)

### OUTPUT

#### Sakai Developer Email Participation by Organization

<img src="week 4-6/screenshot2.png" alt="EmailData-Output">

<p align="center">Sakai Mail Activity by Organization </p>

#### Sakai Developer Email Participation by Organization With One Year Gap

<img src="week 4-6/screenshot3.png" alt="Emaildata-1-year-gap-Output">

## Feedback

Feel free to reach me at [gmail](mailto:aaravmishra619@gmail.com).

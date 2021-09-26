# Visualizing networks and interconnections

In this application, we will perform some of the functions of a search engine. We will first spider a small subset of the web and run a simplified version of the Google page rank algorithm to determine which pages are most highly connected, and then visualize the page rank and connectivity of our small corner of the web. We will use the D3 JavaScript visualization library http://d3js.org/ to produce the visualization output.

You can download and extract this application from:
www.py4e.com/code3/pagerank.zip

## OUTPUT

![PageRank-Output](PageRank_Screenshot.png?raw=true "Page-Rank")

A Page Ranking

The first program (spider.py) program crawls a web site and pulls a series of pages into the database (spider.sqlite), recording the links between pages. You can restart the process at any time by removing the spider.sqlite file and rerunning spider.py.

### For more assistance view : [Week3_README.txt](Week3_README.txt)

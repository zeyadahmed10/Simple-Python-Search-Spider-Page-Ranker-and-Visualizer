# Simple-Python-Search-Spider-Page-Ranker-and-Visualizer

This is the capstone project from [Python for everybody specialization](www.py4e.com).

This is a set of programs that emulate some of the functions of a 
search engine.  They store their data in a SQLITE3 database named
'spider.sqlite'.  This file can be removed at any time to restart the
process.   

You should install the SQLite browser to view and modify 
the databases from:

http://sqlitebrowser.org/

This program crawls a web site and pulls a series of pages into the
database, recording the links between pages.

It uses BS4 for parsing the pages and the visualization in terms of page ranks using d3.v2 (The libraries are incluced)

This visualization is provided using the force layout from:

http://mbostock.github.com/d3/

# Images from the run:
![alt text](https://github.com/zeyadahmed10/Simple-Python-Search-Spider-Page-Ranker-and-Visualizer/blob/main/google.png)
![alt text](https://github.com/zeyadahmed10/Simple-Python-Search-Spider-Page-Ranker-and-Visualizer/blob/main/python-data.png)


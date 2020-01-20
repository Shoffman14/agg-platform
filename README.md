# agg-platform
Aggregation platform initial work


Scrapy in PyCharm
1) Create New Project in PyCharm
2) Click PyCharm in upper left of Desktop, select Preferences 
3) Add Scrapy package
4) Add Crawl package
5) Go back to PyCharm project, open a new Terminal (bottom left)
6) Type scrapy startproject "projectname" & press enter
7) Expand folders of the project (left-side of PyCharm screen)
8) Right-click under Spiders and create New Python File
9) Enter previously written spider code 
10) Updated URL's and respective names for the new spider you are now creating 
11) Open Terminal again and type cd "projectname" & press enter
12) Type scrapy crawl "name" (name from spider code you have pasted in current spider you are working on) & press enter
13) Once spider is done crawling, type scrapy shell "url" (url from current spider you are working on) & press enter
14) Type response.css(".title::text").extract_first() to start extracting titles, etc.
  This final step will be amended throughout project as you are selecting new items from HTML page of website 
  
Jan 19
1) Began writing consolidated spider in PyCharm to pull Brand, Title, and Price of each jean on shopbop webpage
2) Action: Determine how to incorporate XPATH Reference (search & return) on line 43
3) Next Step: Determine how to organize the data pulled from webpage using XPTHA and CSS References 

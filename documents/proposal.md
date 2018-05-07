## Final Project Proposal: EbAbase
Ilana Z. Rubin ([izrubin](https://github.com/izrubin/))

### The Problem

Data about international, development, or humanitarian aid projects is not easily
accessible or searchable from any single source. Instead, there are numerous
sources of project data, with differing search processes, site structures, output
format, and overall ease-of-use. Finding, sorting, and compiling this information
manually is very time-consuming, as I discovered when helping to create a database
of Ecosystem-based Adapatation (EbA) - a type of climate change adaptation - 
projects in mountainous ecosystems in certain regions of the world. The time it 
takes to compile this information manually discourages cataloguing, comparing, 
and evaluating international projects run by different entities that store and 
share their project data in different ways and to different degrees. I would 
like to help reduce the human time burden from performing the searching, 
identification, and compiling of data for projects meeting user-identified 
search parameters.


### The Data

The value of this project increases with the number of data sources I will be 
able to incorporate into one search. I will start with more accessible data 
sources with restful APIs and then aim to add data from additional sources 
through web scraping. My project will be to extract data from these sources and 
potentially others:

+ [USAID](https://www.usaid.gov/developer)
+ [UNdata API](http://data.un.org/Host.aspx?Content=API)
+ [Open UNDP](http://open.undp.org/)
+ [AidData](http://aiddata.org/)
+ Additional potential sources are any of the large funding and implementing 
humanitarian, environmental, or related aid organizations, government agencies, 
or corporations that publish data on their projects.  

### The Tools

+ Languages: Python for coding, HTML within web scraping, and potentially JSON
+ Jupyter notebooks for tutorials and testing code
+ Web scraping tools
	+ [Requests](http://docs.python-requests.org/en/master/user/quickstart/)
	+ [Scrapy](https://scrapy.org/)
	+ [Beautiful Soup](http://beautiful-soup-4.readthedocs.io/en/latest/)
	+ Potentially [Selenium](http://selenium-python.readthedocs.io/index.html)
	if needed as a Web Driver
+ Pandas for formatting dataframes of returned records
+ Bokeh, or other tools for interactive data and map visualization in a 
hypothetical longer version of this project.

### The Novelty

When searching for information about many development projects at once, there is
currently no single source or program that someone can go to that not only offers
a comprehensive source as well as a user-friendly interface with modifiable 
output options. There are different sites that have some of those features, and 
while this project will not reasonably accomplish all of this, it is a step 
toward doing so. That there is no currently available, or at the very least not 
well-known option for this already is evidenced by my experience in which one of 
the largest international environmental organizations tasked a team of graduate 
students with compiling information for a database of projects including mountain 
EbA, rather than turning to a single-stop resource that would ideally automate
much of this process.

### The Goal

My first envisioned product is a Jupyter notebook tutorial for streamlining the 
process of searching and obtaining information about aid and development projects 
with specific parameters, instead of the user having to manually search and read 
through numerous project descriptions on numerous sites to find matches. I would 
demonstrate this with search parameters for Ecosystem-based Adaptation (EbA) 
projects, but would ideally create an importable package with variable parameters 
so that users can search for any type of aid or development project, and return 
well-formatted output data. While the initial goal would include effeciently 
searching, obtaining, and formatting records from one data source, I would want 
to include as many large and reliable project data sources as possible, saving
users additional time. An ultimate goal that I do not expect to achieve at this 
time is to create a GUI program for non-coding users to search from one place
across multiple project data sources for any type of development project, with 
options to return the record data in different formats (interactive maps with 
project summaries, tables, raw data) depending on user preference. Much further
hypothetical development could include analysis of different types of aid project
data, increasing transparency around humanitarian aid.

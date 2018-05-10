# EbAbase

## Project Description
EbAbase is a final project developed during the Programming & Data Science Skills course to create a package for scraping the web for international aid project information and returning that in formatted dataframes. EbAbase is specifically focused on gathering project information from multiple sources (USAID, UNDP, and more) in order to build a database of mountain Ecosystem-based Adaptation (EbA) projects, with potential for wider application in querying and return project data fitting other search parameters.

## Installation Instructions
Enter the following commands in a terminal in order to install this EbAbase repo and package.
```python
git clone https://github.com/izrubin/EbAbase
cd EbAbase/
pip install .
```

### Dependencies
```python
conda install requests pandas scrapy
```

## Instructions to Find Examples in the Notebooks Directory
To access the Jupyter notebooks for EbAbase examples, navigate to the `notebooks/` directory, open Jupyter notebooks, and run the EbAbase tutorial notebooks. The first notebook goes through the process of using a RESTful API for USAID Development Experience Clearinghouse metadata. The second notebook would have gone through web scraping sources without RESTful APIs. A third notebook would have demonstrated importing and using a package I would have developed from functions through the first two notebooks. Enter the following lines in a terminal _after_ following the installation instructions above in order to access the Jupyter notebooks. Alternatively, you can view the notebooks in a non-executable format through GitHub [here](https://github.com/izrubin/EbAbase/tree/master/notebooks).
```python
cd notebooks/
jupyter-notebooks
```

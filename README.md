# GitHub Topics Scraper
Scrapes GitHub Topics (https://github.com/topics) page. Creates a CSV file for each of the top 30 topics, the CSV files contain the name, username, stars, and URLs for the top 25 repositories of the respective topic.

# Libraries:

## Requests
Requests allows you to send HTTP/1.1 requests extremely easily.

#### Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requests

```bash
$ python -m pip install requests
```

## Pandas
Pandas allows importing data from various file formats such as comma-separated values, JSON, SQL, Microsoft Excel. Pandas allows various data manipulation operations such as merging, reshaping, selecting, as well as data cleaning, and data wrangling features.

#### Installation
Follow the instructions on the pandas website https://pandas.pydata.org/getting_started.html to install the library.


## OS
We use os.path to check if a CSV file with the same name of the file we want to create already exists, and os.makedirs to create a folder to store the CSV files.

#### Installation
OS is a python standard library, no need to download it.

```bash
import os
```

## beautifulsoup4
Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree.

#### Installation 
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install bs4

```bash
pip install beautifulsoup4
```


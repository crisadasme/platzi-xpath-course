# XPATH SCRAPING - PYTHON

This repository contains working code which gather all news news from a famous Colombian website and saving them into each corresponding text file with its own Title, Summary and Body. 

# Functionality
Code is pretty straightforward, being able to fetch different news from [LarRepublica.co] (https://larepublica.co) and saving them into a folder with the current day (using format d-m-Y). At this day (01-05-2021), the code is working correctly with no problems, but it is posible to get some issues if the target url change some attributes or hierarchy order inside of its source code.

# XPATH
Every xpath string are listed into xpath.txt file and each one of them was tested directly on Chrome Console before to be implemented into the python's code. This xpath.txt file contains a brief reference of how its work, being really intuitive to understand. 

# Requeriments
All modules used it are listed into requirements.txt file which its corresponding version. You can install all at once using next command line:

```sh
# Python 3
$  pip install -r requirements.txt
```

# Running Code
```sh
# Python 3
$  python3 scraper.py
```

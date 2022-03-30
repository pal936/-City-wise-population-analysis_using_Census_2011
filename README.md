# -City-wise-population-analysis_using_Census_2011
INTRODUCTION
•The Census of India conducted every 10 year's in India.

•First census Started in 1871. The word 'Census' came in the Latin word 'Censere' and the 'Censere' meaning to assess. Or other word Census meaning 'an official count or survey, especially of a population'.

•Census is nothing but a process of collecting, analyzing, evaluating, publishing and discripting statistical data regarding the population.

This repository consists of the following:
README.txt (this file)
Dataset : "Census.csv"
Notebook downloaded as an ipynb file
"Web-scraping_Using_2011_Census_of_India" consists of scraping websites and creating dataframes.
"Data_Analysis_Using_2011_Census_of_India" consists of analyzed data.
Step 1 : IMPORTING LIBRARIES:
We are import many libraries as per our needed:-

import pandas as pd # used for data analysis.
import numpy as np # used to perform mathematical operations on arrays.
import re # to check if a string contains the specified search pattern.
import requests # allow you to send HTTP/1.1 requests using Python.
from bs4 import BeautifulSoup # web scraping purposes to pull the data out of HTML and XML files.
import matplotlib.pyplot as plt # used to data visualization.
import seaborn as sns # making statistical graphics in Python.
from tabulate import tabulate # used to print tabular data in nicely formatted tables.
Step 2: Clear the data
1.We make a lot of things clear in web scraping: -
Remove ',','' etc.
Change the data type as per our requirement.
2. In data analysis we are only removing the "Nameless: 0" column.
Step 4 : SUMMARIZING THE DATASET
Dimensions of the dataset
Peek at the data
Statistical Summary
Class Distribution
Information about data
Length of the data
Let's following questions:-
Total number of cites as per state?
Population wise highest rank city in India.
population wise least city in India.
Check highest LITERACY city in India.
Check lowest LITERACY city in India.
Etc. ►"All the question of the answer are showing using ghraph and table format in "Data_Analysis_Using_2011_Census_of_India""
Conclusion
•We are using Census 2011 of India for our dataset.

•Analyzing our data, we can see that Uttar Pradesh has the highest number of cities and there are 64 cities in Uttar Pradesh.

•The highest city in India by population is Mumbai (Maharashtra) and population is 12442373.

•The lowest city in India by population is Kupurthala (Panjab) and population is 98916.

•The highest city in India by litaracy is Aizawl (Mizoram) and percentage is 98.36%.

•The lowest city in India by litaracy is Sambhal (Uttar Pradesh) and percentage is 48.98%. And we see that the total population of Hyderabad is 6731790 and the literacy percentage is 83.26% and

•Hyderabad is the 4th most populous city in India according to our data.

Thank You

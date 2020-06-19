# IBM Data Science Professional Specialization Capstone Project

This Repo contains the Applied Data Science Capstone-Project for the IBM Data Science Professional Certification Specialization program designed and taught by IBM via Coursera. This Capsone-Project is the final course in a series of nine(9) Data Science Specialization courses which include the following courses:-

1. [What is Data Science?](https://www.coursera.org/learn/what-is-datascience/home/welcome)
2. [Open Source tools for Data Science](https://www.coursera.org/learn/open-source-tools-for-data-science/home/welcome)
3. [Python for Data Science](https://www.coursera.org/learn/python-for-applied-data-science/home/welcome)
4. [Data Science Methodology](https://www.coursera.org/learn/data-science-methodology/home/welcome)
5. [Databases and SQL for Data Science](https://www.coursera.org/learn/sql-data-science/home/welcome)
6. [Data Visualization with Python](https://www.coursera.org/learn/python-for-data-visualization/home/welcome)
7. [Data Analysis with Python](https://www.coursera.org/learn/data-analysis-with-python/home/welcome)
8. [Machine Learning with Python](https://www.coursera.org/learn/machine-learning-with-python/home/welcome)
9. [Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone/home/welcome)

#### It is mandatory that all courses from 1 to 8 are passed with acceptable grades before attempting The Capsone-Project.**

<p align="center">
  <img src="https://github.com/Lawrence-Krukrubo/IBM_Data_Specialization_Capstone_Project/blob/master/IBM-badge_data-science-professional-certificate.png?raw=true" height=400 width=500 alt="IBM_Data_Specialization_badge">
</p>

##### Completing this Project earns the prestigious IBM Data Science badge. The badge earner is ready for a career in data science with demonstrated ability to solve for real-world problems. They can apply Data Science methodology - work with Jupyter notebooks - create Python apps - access relational databases using SQL & Python - use Python libraries to generate data visualizations - perform data analysis using Pandas - construct & evaluate Machine Learning (ML) models using Scikit-learn & SciPy and apply data science & ML techniques to real location data sets.

## Project Overview:

This capstone project course is a taste of what data scientists go through in real life when working with data. 

I will apply practical knowledge about location data and different location data providers, such as Foursquare and use this to make RESTful API calls to the Foursquare API to retrieve data about venues in different neighborhoods around the world. I will also be creative in situations where data are not readily available by scraping web data and parsing HTML code. 
I'd work with Python and its pandas library to manipulate data, which will help refine my skills for exploring and analyzing data. 

Finally, I will use the Folium library to great maps of geospatial data and to communicate my results and findings.

### Project Structure

1. <h4>Introduction:</h4>

In this module, you will learn about the scope of this capstone project and the context of the project that you will be working on. You will learn about different location data providers and what location data is normally composed of. Finally, you will be required to submit a link to a new repository on your Github account dedicated to this course.

2. <h4>Foursquare API</h4>:

In this module, you will learn in details about Foursquare, which is the location data provider we will be using in this course, and its API. Essentially, you will learn how to create a Foursquare developer account, and use your credentials to search for nearby venues of a specific type, explore a particular venue, and search for trending venues around a location.

3. <h4>Neighborhood Segmentation and Clustering:</h4>

In this module, you will learn about k-means clustering, which is a form of unsupervised learning. Then you will use clustering and the Foursquare API to segment and cluster the neighborhoods in the city of New York. Furthermore, you will learn how to scrape website and parse HTML code using the Python package Beautifulsoup, and convert data into a pandas dataframe.

4. <h4>The Battle of Neighborhoods:</h4>

In this module, you will start working on the capstone project. You will clearly define a problem and discuss the data that you will be using to solve the problem.

5. <h4>The Battle of Neighborhoods (Cont'd)</h4>

In this module, you will carry out all the remaining work to complete your capstone project. You will submit a report of your project for peer evaluation.

### My Project:

* <h4>Problem Description:</h4>
The problem I want to solve using Geo-location Data is helping a new Tech-StartUp find the ideal location for its office in The City of Lagos Nigeria. This office should be situated in a good location that has the following:-

Central location.<br>
Close proximity to Tech-Hubs and talent.<br>
High feet traffic area for easy interaction with potential customers.<br>
Nearness to Educational institutions for research and interactions with academics.<br>
Nearness to cafes and restaurants for business meetings or lunch-meets.<br>
Nearness to bus-stops, seaports and airports.<br>
Security and safety.<br>
Cluster of economic activities and similar or complementing businesses.

* <h4>Background to Problem:</h4>

I have lived in Lagos for some time off and on, longest has been 3 years stretch from 2006 to 2009.
I have also done some travelling to other countries such as Russia, which by the way is the largest country in The World by land mass, South-Africa, Ghana, Dubai, Mauritius and a few others.
By the way, Mauritius is The wealthiest country in Africa with average wealth per person increasing from $(21700 - 25700) within one year recently ([link](https://www.graphic.com.gh/business/business-news/accra-ranked-10th-wealthiest-city-in-africa.html)).
My analysis today is on Lagos state, which is the 4th wealthiest city in Africa, fourth place behind Johannesburg, Cairo and Cape Town ([link](https://www.graphic.com.gh/business/business-news/accra-ranked-10th-wealthiest-city-in-africa.html)).
Lagos city is home to over $$(6,800 millionaires, 370 multi-millionaires and 4 billionaires).
Lagos is also the commercial capital of Nigeria (The Most populous black nation), and the commercial hub of West Africa.
I have only recently returned to Lagos city in 2019, got enrolled and completed The Founder Institute programme and currently building a Startup in The Insuretech industry (link).
Therefore I want to use this opportunity to help future Startups find the most ideal location in Lagos city, for an office.

* <h4>Data Requirements and Overview:</h4>

The Dataset is the wikipedia page of Lagos state.

I shall explore Lagos city through its respective Local Government Areas or Boroughs. The wikipedia link is a web page that shows the respective boroughs in Lagos State and each population figure. It's a public Wikipedia data page.
This data will be analysed through the following steps:-

I shall scrape the web page using the beautiful soup library<br>
I shall use The Foursquare API calls to retrieve geolocation data<br>
I shall fetch the text data using the requests library<br>
I shall convert it from JSON to Pandas data frame using the json_normalize module<br>
I shall use The folium library to render the maps and plot these via The Matplotlib library.<br> 
Then I shall explore respective boroughs and analyse each area as a location for a Tech-Startup based on the aforementioned parameters.<br>
After this, I shall select our top location.<br>

Finally, to add some fun, I shall use the word-cloud library to display the names of the top categories of venues per borough.

My Project Notebook can be seen above in the **applied_data_science_capstone_project.ipynb** file.

### Dependencies:

To follow along replicating this project in your own local IDE, kindly install and import the following modules.

* `import pandas as pd`
* `import numpy as np`
* `from bs4 import BeautifulSoup`
* `import requests` (library to handle requests)
* `import json`  (library to handle JSON files)
* `from pandas.io.json import json_normalize`  (transform json files to pandas dataframes)
* `from geopy.geocoders import Nominatim`  (convert an address into latitude and longitude values)
* `import csv`

**Import matplotlib and its attendant attributes**
* `import matplotlib.pyplot as plt`
* `import matplotlib.cm as cm`
* `import matplotlib.colors as colors`

**import k-means for clustering stage**
* `from sklearn.cluster import KMeans`

**install and import folium library for plotting interactive maps**
* `!conda install -c conda-forge folium=0.5.0 --yes`
* `import folium` (map rendering library)

### Blog-Post:

Feel free to understand the logic behind the project and each method and code I wrote by reading this really cool article in [The Medium](https://medium.com/towards-artificial-intelligence/geolocation-data-analysis-of-lagos-b2b4f39ac5e7)


### Certifications:

Here's a link to my Capstone Project Completion [**certificate**](https://coursera.org/share/8b78de4619b79b35d81169e7635ff190)<br>
Here's a link to my IBM Data Science Professional Specialization [**certificate**](https://coursera.org/share/a16f28c0c3ed4e65d7629841847b200b).

### License:

All codes, documents, anlysis and files for this project abide under the **MIT** license in the root-directory of the project.



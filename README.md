# College Basketball Analysis

## Introduction
The basis of this project is to determine and analyze what makes a good college basketball team and view these trends over time. By doing a few methods of statistical analysis, we are able to view which teams should be considered the best of the best and teams going forward can improve.

## Overview
The basis of this project was to create a tutorial that follows the Data Science Pipeline, as learned in class. Each part of the pipeline should be followed and read carefully in order to understand what is happening at each step of the process. The steps are:
1. Data Collection
1. Data Processing
1. Exploratory Data Analysis and Visualization
1. Hypothesis Testing and Machine Learning
1. Final Thoughts

## Tutorial

### Step 1 - Data Collection
Data was collected utilizing the requests and BeautifulSoup4 libraries. By figuring at the schematic layout of the website we were trying to scrape, we figured out how to effectively grab information from each necessary page. We then compiled all of this data into what dataframe. Only statistical data from the AP Final #1 teams was collected because those teams are widely regarded as the best throughout their respective season.

### Step 2 - Data Processing
The next step, processing, is one of the most needed yet least enjoyable parts of the data science pipeline. Processing is crucial for analyzing the overall college basketball data. We used proper data science practice to make sure the dataframe has labels and variable names that are accurate and concise and match the original scraped dataset.

### Step 3 - Exploratory Data Analysis and Visualization
Here is the most visual and interesting part of the process. After data is properly organized and processed, we can then create graphs, charts, and statistical summaries of any problem we are trying to explore. We even created our own basketball statistics utilizing a combination of stats in order to better understand trends over time.

### Step 4 - Hypothesis Testing and Machine Learning
Linear regression is the simplest form of machine learning, yet it is also very powerful. It can help establish trend indications across time. For example, in our tutorial, we were able to look at one offensive statistic that is vital to winning and how it increased with a type of basketball shot. You could then extrapolate that in the future, teams will be more efficient in their scoring if they follow our model. Also, we used hypothesis testing to see the goodness of fit of our model on the data in order to see if this actually an effective predictive measure.

### Step 5 - Final Thoughts
Conclusions and reflections are important for projects and in life. We hope that this project garners more interest in the ever growing interdisciplinary studies of data science and sports.

## Installation 
Install the requirements here
```
pip install -r requirements.txt
```

## Built With

* [Jupyter Notebook](https://jupyter.org) - Python Notebook Interface
* [Pandas](https://pandas.pydata.org) - Data Analysis Library
* [Requests](https://requests.readthedocs.io/en/master/) - HTTP Library
* [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Web Scraping Library
* [numpy](https://numpy.org) - Scientific Computing Library

## Authors

* **Evan Devore** - [Github Repo](https://github.com/edevore)
* **Mat Steininger** - [Personal Site](https://mathewsteininger.com)

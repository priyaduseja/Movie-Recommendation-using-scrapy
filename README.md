# Movie Recommendation System using Scrapy

**Overview**
This project implements a movie recommendation system that scrapes data from IMDb's list of top-rated movies to gather information about directors and their top four movies. The system utilizes Scrapy, a web crawling and web scraping framework, to extract relevant data from IMDb's website.

**Description**

**Implementation**
1. **Spider Definition:**: The project defines a Scrapy spider named MovieRecommendation. The spider starts by visiting IMDb's list of top-rated movies.
2. **Data Extraction:**
  a. The spider extracts movie names and their respective URLs from the initial page.
  b. It follows each movie URL to extract information about the movie's director.
  c. From the director's page, it gathers details about the director's top four movies.
3. **Data Storage:**: The extracted data, including movie names, director names, and top four movies, is stored in a CSV file named MovieRecommendation_using_scrapy.csv.

**Dependencies**
Python 3, Scrapy

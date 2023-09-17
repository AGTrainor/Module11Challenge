# Module11Challenge

The submission contains two jupyter files:
1: scrape titles & preview text from Mars news articles
2: Scrape and analyze Mars weather data

For this challenge, I scraped data from two different websites and anlyzed and visualized teh data. 

Part 1: Scrape Titles and Preview Text from Mars News

To scrape the titles and preview text from Mars news articles, I used the following steps:
I used the Splinter library to visit the Mars news website.
I used the BeautifulSoup library to parse the HTML code of the website and extract the titles and preview text of the news articles.
I stored the scraped data in a list of Python dictionaries, with each dictionary containing a title and preview key.
I printed the list of dictionaries to the console.

Part 2: Scrape and Analyze Mars Weather Data

To scrape and analyze the Mars weather data, I used the following steps:
I used the Splinter library to visit the Mars Temperature Data Site.
I used the BeautifulSoup library to parse the HTML code of the website and extract the data in the HTML table.
I stored the scraped data in a Pandas DataFrame.
I examined the data types of the columns in the DataFrame and converted them to the appropriate datetime, int, or float data types.
I used Pandas functions to answer the following questions:
  How many months exist on Mars?
  How many Martian days' worth of data exist in the scraped dataset?
  What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  Which months have the lowest and the highest atmospheric pressure on Mars?
  About how many terrestrial (Earth) days exist in a Martian year? 
I created data visualizations to support my answers to the above questions.
I exported the DataFrame to a CSV file.

I completed this assignment on my own with class resources and online matierals. 

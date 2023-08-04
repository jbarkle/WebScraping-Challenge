# WebScraping-Challenge
### Info / Credits

- Project by 
    * `jbarkle` 

- `REPO:` https://github.com/jbarkle/WebScraping-Challenge

## Introduction

This project consists of two technical products, including the following deliverables:

- Deliverable 1: Scrape titles and preview text from Mars news articles.

- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News

- Used automated browsing to visit the Mars news site.
- Created a Beautiful Soup object and used it to extract text elements from the website.
- Stored each title-and-preview pair in a Python dictionary, then stored dictionaries in lists
- Printed the list

## Part 2: Scrape and Analyze Mars Weather Data

- Used automated browsing to visit the Mars Temperature Data site.
- Created a Beautiful Soup object and used it to scrape the data in the HTML table. (did not use read_html)
- Assembled the scraped data into a Pandas DataFrame.
- Casted the data to the appropriate datetime, int, or float data types.
- Analyzed the dataset by using Pandas functions to answer the following questions:
    >- How many months exist on Mars?
    >- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    >- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    >- Which months have the lowest and the highest atmospheric pressure on Mars?
    >- About how many terrestrial (Earth) days exist in a Martian year?
- Exported the DataFrame to a CSV file.
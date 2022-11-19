# Amazon-Web-Scraping

## Task
Create a web scraping tool that obtains a products name and price from Amazon's website at a specified interval. Then take this data and store it into a CSV file.

## Components
- P1. Google Colab Notebook containing the code

## Background
Followed youtube tutorial to learn basic of web scraping.
\n Link: https://youtu.be/HiOtQMcI5wg?t=1420

## Approach
1. Import and use beautifulsoup, requests, and smtplib libraries to connect to website for HTML collection.
2. Import and use time and datetime libraries to date each price recording.
3. Use developer toolbox in chrome to obtain segments of HTML that correspond with desired information such as product name and price.
4. Create CSV file to record data.
5. Obtain data and record to CSV file at specified interval

## Technology Stack
- Google CoLab Notebook
- Python
  - BeautifulSoup
  - requests
  - smtplib
  - time
  - datetime

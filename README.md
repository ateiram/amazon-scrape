# amazon-scrape

- A simple amazon scraper to extract bestseller books' details and prices from Amazon.com using Python Requests and Beautifulsoup. 

- User agent is set, so the amazon lets us view the content. 
- -999 is used as a way of imputation for unavailable/missing data 
- Some basic Regex and manipulations were used to improve data for further use. 
- Complex search is done by finding the book title that has the highest number of occurences from the searched string

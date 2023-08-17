# Mars-WebScraping-DataAnalysis
This project consists of two parts, scrape titles and preview text from Mars news articles, and Scrape and analyze Mars weather data, which exists in a table.

### Deliverable 1: Scrape titles and preview text from Mars news articles by doing the following:

- Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to extract text elements from the website.
- Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
    - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
    - Store all the dictionaries in a Python list.
    - Print the list in notebook.
    - export the scraped data to a JSON file

### Deliverable 2: Scrape and analyze Mars weather data, which exists in a table by doing the following:

- Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to scrape the data in the HTML table. 
- Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
- Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate
- Analyze the dataset by using Pandas functions to answer the following questions:
    - How many months exist on Mars?
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    - Which months have the lowest and the highest atmospheric pressure on Mars?
    - About how many terrestrial (Earth) days exist in a Martian year?
- Export the DataFrame to a CSV file.

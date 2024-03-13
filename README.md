# Rival-and-Price-Analysis-Project-with-Web-Scraping

<img src = "images/web_scraping_home.png" style = "width:1025px; height:450px"/>

## Business Problem

A company that sells books online has noticed a decline in sales within the "Travel" and "Nonfiction" categories.

Therefore, the company needs to scrape data from the website: https://books.toscrape.com/, specifically targeting books in the **"Travel"** and **"Nonfiction"** categories, to conduct competitor and price analysis.

The company requests you to navigate to the detail pages of each book in these categories and retrieve specific information from there.

## Project Flow Required

**1. Obtaining Category Page Links:** In the first step, links to pages containing books in the "Travel" and "Nonfiction" categories should be extracted from the homepage.

**2. Scraping Category Pages and Extracting Book Links:** In the second step, pages for each category should be opened, and links to access the detail pages of books on these pages should be scraped.

**3. Scraping Book Detail Pages:** In the third step, using the scraped book links, each book's detail pages should be visited, and the information should be scraped.

**4. System Automation:** Finally, a system should be automated to perform these steps for other categories as well.

## Requirements

- Python 3.9.13
- Web scraping libraries such as BeautifulSoup, Selenium and requests
- Anaconda or virtual environment tool (e.g., virtualenv)

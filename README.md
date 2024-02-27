## Web-Scraping-for-Amazon-Bestseller-Books
This project is a Python-based web scraper that retrieves information about best-selling books from Amazon. It extracts data such as rank, title, author, and price for each book and stores it in a structured format for further analysis.

**Overview**

The scraper navigates through Amazon's best seller books page, extracts information about each book, and organizes it into a pandas DataFrame. It then exports this DataFrame to a CSV file for easy access and analysis.

**Data Source**

The data for this project is sourced from Amazon's best seller books page https://www.amazon.in/gp/bestsellers/books .The scraper retrieves information about the top-selling books listed on this page.

**Requirements**

- Python 3.x
- BeautifulSoup4
- Pandas

**Output**

Upon running the web scraper script, the following output is generated:
`Amazon best seller books.csv`

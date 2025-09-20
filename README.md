# Book Data Analysis from BookstoScrape
This project focuses on extracting and analyzing data from the Books to Scrape website. The goal is to assist a startup bookstore in making informed decisions about its book inventory by identifying popular book categories and current market price trends.
# Business Problem
The bookstore needs actionable insights into current book price trends, customer preferences, and competitive offerings to decide which categories to stock. This project addresses that need by extracting and analyzing data from the Books to Scrape website.

# Objectives
Price Trend Analysis: To analyze the price trends of books within each category and compare them against the market average.

Identifying Popular Book Categories: To find the most popular book categories based on customer ratings and reviews.

Stock Management: To identify which types of books are in high demand in the market.

# Business Questions
Which book genres have the highest average ratings and reviews from customers?

How do book prices differ across categories, and what are their price trends over time?

Which books are frequently out of stock, and what does this indicate about popularity or supply issues?

# Installation
This project uses the following Python libraries:

urllib.request (built-in)

BeautifulSoup

pandas

# You can install the necessary libraries using pip:
`
pip install beautifulsoup4 pandas
`
# How to Run
The project is developed as a Jupyter Notebook. The file contains sample code that demonstrates various data extraction and analysis tasks, including:

Extracting all book data to create a CSV file.

Scraping book categories along with their links.

Extracting links to detail pages for each book.

Scraping detailed information from each book's page and storing it in a pandas DataFrame.

You can run the code by opening the .ipynb file with Jupyter Notebook or JupyterLab.

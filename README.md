# SCRAPING THE BEST SELLER BOOKS OF 2020

### Goal
The goal of this study is to get Best-Seller Books of 2020 by using web scraping libraries of Python.

### Stages
* The data is fetched from web by scraping the amazon's web site by using Python Beatifulsoup library.
* The extracted fields are name, author, rank, user_Rating, number of users rated and the price of the book.
* After all 100 books info is taken, it is converted into a data frame.
* Some preprocessing is applied to the columns that are fetced as string but should be inherently numbers.
* The top rated and highest priced books are plotted in a graph.

### Libraries Used
* pandas
* requests
* BeautifulSoup
* matplotlib

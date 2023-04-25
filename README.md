# God of War Steam Reviews Scraper

This is a Python project that uses Selenium and Beautiful Soup libraries to scrape the top-rated reviews of God of War on Steam. The need for Selenium came from the fact that
Steam review pages are infinitely scrolling. Without scrolling the page has only 10 reviews.

### Installation 

To run this project, you need to install the following libraries:
* beautifulsoup4
* pandas
* selenium
* webdriver_manager

To install these libraries, you can use pip, a package manager for Python. Simply run the following command:

pip install beautifulsoup4 pandas selenium webdriver_manager


### Usage

To use this project, run the code in your Python environment. The code will open up a browser using Selenium and scroll down the page to load more reviews. It will then scrape the HTML using Beautiful Soup and parse the data into a Pandas DataFrame.

By default, the code scrapes the top-rated reviews of God of War on Steam. However, you can modify the URL in the code to scrape reviews based on different criteria. Simply change the url variable in the code to the desired URL.

The scraped data is stored in a Pandas DataFrame. You can use Pandas functions to further analyze and visualize the data.

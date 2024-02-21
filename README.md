# web-scrapping-with-javascript-tables-using-Python-selenium

## Summary ##
In conclusion, scraping JavaScript tables with Python is a powerful way to extract data from websites and use it for a variety of purposes. Whether you are using your own code or a professional scraper, this technique can be a valuable tool for gathering data and gaining insights.

In this project, I will scrape the medicine data that is public by the MoH in the Vietnamese market, this dataset can be used for various purposed like pricing analysis, master data file for medicine data, etc.

The link to the dataset: https://dichvucong.dav.gov.vn/CongBoGiaThuoc/index

Now, Let's start scrapping.

## What is a JavaScript table ##
JavaScript tables are a common way to display tabular data on the web, and they can be found on a wide range of websites. Scraping these tables can be challenging because the data is often embedded in the page's source code as a JavaScript object, rather than in a standard HTML table, which means there is no table id and we cannot store it in a normal variable. However, with the right tools and techniques, it is possible to extract this data using Python.

## Steps in scrapping data ##
### Step 1: Loading the webpage ###
The first thing we need to do is load the webpage containing the table that we want to scrape. We can do this using Selenium and a web driver.
we'll create an instance of the web driver and use it to load the webpage

### Step 2: Extract the data ###
Once the webpage is loaded, we can use Selenium to extract the data from the table. There are several ways to do this, but one method is to use the driver.find_elements(By.CSS_SELECTOR, ‘td’) or By.XPath function in my case to locate the cells in the table and extract the text from each cell.

### Step 3: Store and manipulate the data ###
Detail in the notebook

## Execise ##
Here is the webpage with similar html code. The link is below and the notebook is also attached, please use it for review.
https://hososuckhoe.net/tien-ich/y-te-toan-quoc.html#!#danhsachcoso

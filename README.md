<p align="center">
<img src="images/macarons-3953465_960_720.jpg" width="600" />
</p>

# **WebScraping**

**To access the notebook [click here](https://github.com/Raoni-Silva/bookWebscraping/blob/main/Tea%20O'Clock%20webscraping%20with%20BeautifulSoup.ipynb).**

## **1. Business Context**

The Tea O'Clock is a tea shop in London that wants to become a book club where people come to have a quiet and pleasant time.

Tea O'Clock wants to have a good but small selection of books and after a market research they've decided to keep only books from the following category:

  **- Classics** <br>
  **- Science Fiction** <br>
  **- Humor** <br>
  **- Business** <br>

In order to decide which books to have on their store I've been asked to build a dataframe including the following infos:

  **- Book name** <br>
  **- Book price (in pounds)** <br>
  **- Customer rating** <br>
  **- Stock availability** <br>

## **2. Strategy**

### 2.1 The output

The output will be a csv file containing the following informations:

|column names|description|
|-----|-----|
|book_title|The title of the book|
|book_price|The price of the book in pounds|
|book_rate|The book customer rating from 1 to 5|
|book_availability|Shows if the book is available in stock|
|book_category|The category of the book|
|scrap_time|The date and time the scrap was done|


### 2.2 Tools

The tools used in the process:

**- Python 3.9** <br>
**- Jupyter Notebook** <br>
**- Internet browser**<br>

The libraries used in the process:

**- BeautifulSoup** <br>
**- Pandas** <br>
**- Requests** <br>
**- Datetime** <br>
**- Regex** <br>

### 2.3 Steps

**STEP 01:** Understanding the website structure using an internet browser in order to find where the needed data is allocated.

**STEP 02:** Scrap the root page to get the urls of the choosen categories.

**STEP 03:** With the list of urls, scrap the data of the books.

**STEP 04:** Create a dataframe with all the data gathered.

**STEP 05:** Export the data into a csv file and send it to the Tea O'Clock shop.


### 2.4 Source:

The data was gathered from https://books.toscrape.com, a website made for webscrap training for free.

## 3. Next Steps

- Change the code in order to have more flexibility to choose the categories needed.
- Create a streamlit for a better usage of the data.
- Use streamlit as a catalogue of the Tea O'Clock book stock.


# webscraping
# Scraping the software data from a website, such as company name, rating, description etc and exporting the data to a .xlsx file.
In this project, https://www.g2.com/search?utf8=%E2%9C%93&query=salesforce&button= website is been used for the scrapping. The goal was to scrape the title, rating, & description data of salesforce company products from the website.
First we have downloaded the results of "salesforce" which is 63 pages and the website was using a cloudflare to prevent bot/ddos actions and to bypass that we've used "Scrapper API".
Using Scrapper API we have downloaded the <.html> files which are the pages of the search results for salesforce on the website, and then we've parsed the title, rating, and description data, and inserted the scraped data into a pandas dataframe. 
We have closed the project by exporting the dataframe into <xlsx> file.

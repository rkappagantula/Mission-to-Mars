# Mission-to-Mars
#### *HTML Web scraping on Mars data to create a Flask web application using Python and MongoDB*

## Overview
This project consisted on a Python script to scrape text and images from various websites that talked about Mission to Mars. A Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without having to gather it manually. The data scraped and displayed was stored in a non-relational Mongo database. A scraping script was created so that each time a button was clicked, the scraping occurs and database is updated, with new data to be displayed. A responsive web app was created for enhanced user experience using Bootstrap Grid System.

## Resources 
- Web pages scraped: 
  - https://data-class-mars.s3.amazonaws.com/Mars/index.html
  - https://spaceimages-mars.com
  - https://galaxyfacts-mars.com
  - https://marshemispheres.com/
- Software:
  - Python
  - Jupyter Notebook
  - Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo
  - MongoDB
  - HTML5
  - Bootstrap 3

## Summary

The web application created with Flask that included images, a table with information about Mars in comparison to Earth, and the latest article title and short description scraped from the NASA's webpage. Each time we click on the "Scrape New Data" button new information will be updated on both the website and the MongoDB.


The scrape included a `news_title` with its brief explanation (`news_paragraph`), a `featured_image`, a table HTML component stored in `facts`, and four picture thumbnails, with their titles, of the different Mars' hemispheres stored in `hemispheres`. 

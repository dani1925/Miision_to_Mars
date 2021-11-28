# Mission to Mars

This repository contains the most recent information about Mars collected directly from the NASA website,

The information is stored in a local database using Mongo
and it is displayed through a local server using Flask

## Web Scrapping

In order to perform data acquisition, the "BeautifulSoup" library was used to obtain the HTML file of the desired website and perform the text acquisition within it.The Script automatically navigates to two different websites automatically


## Mongo

MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas.

For this specific application mongo is the best option to store the "scrapped Data"

## Flask

Once the data was acquired from the web sites, and once they have been saved in the database, the best option must be found to display the results.

FLASK liberia is used as a local web server to display our results in web browser

The HTML template is shared in the Templates folder



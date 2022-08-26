# Mission to Mars

## Overview and Purpose

Robin is looking for a way to gather information regarding the amount of water on Mars from all over the web and display it all in one location. She needs to develop a web application that scrapes information using a nonSQL database and Flask. To help her out, we created a python code on Jupyter Notebook that scraped the web for images, news headlines, and facts about mars from a collection of websites. The scraper was run successfully and managed to find many images from across the web of Mars's hemispheres, shown below. 

![](hemi_img_urls.png)

## Method and Analysis

For this project, a python file was created for the scraping that would be required for the application to work. Once that was done, the file was imported onto the application file along with PyMongo and Flask. The template for the application was set as the index.html file, which was coded to display the web scraper and the images on the main site. Upon running the application on Flask, the page that opens contains a title, a background picture, a scrape button, a featured picture, a table of facts about Mars, and a section about the various hemispheres of the planet.

![](mars_site.png)
![](hemispheres.png)

For the third deliverable, the html code was edited to display the web scraper in a mobile device setting.

![](mobile.png)

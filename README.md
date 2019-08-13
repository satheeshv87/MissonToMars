# MissonToMars

In this project, data is scrapped from several mars websites (including mars twitter handle), inserted data into Mongo DB database and then data retrived from Mongo DB and displayed in web.

# Web Data Sources
<https://mars.nasa.gov/news> <br>
<https://twitter.com/MarsWxReport> <br>
<https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars> <br>
<https://space-facts.com/mars/> <br>
<https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars>

# Tech Stack Used:
- Beautiful Soup to scrap the web
- Selenium splinter to navigate through web pages
- Mongo Db NOSQL database to store the scraped data
- html, css, Flash API for front end display

# Final Output
If 'Scrape New Data!' is clicked, data from the web is scraped, stored in Mongo DB and then returned to the same web page within seconds.

![MarsPart1](https://user-images.githubusercontent.com/22437603/62915982-7d6a2b80-bd64-11e9-9faf-d8add3b26c05.PNG)
![MarsPart2](https://user-images.githubusercontent.com/22437603/62915992-88bd5700-bd64-11e9-9fea-beb233dbc2ff.PNG)

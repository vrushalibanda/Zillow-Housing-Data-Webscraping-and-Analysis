# Zillow-Housing-Data-webscraping-and-Analysis 


In this project, I scraped data from Zillow website using different Python packages including Beautiful Soup. Data scraping was especially interesting to me since I learnt how I could suddenly gather data from so many new sources that I found difficult before. Once I scraped this data, I cleaned the data and performed exploratory data analysis, to understand housing price trends in the Bay Area. Certainly, Palo Alto was expensive. But the more interesting observation was that the price difference between a 2br and a 3br house is not so much different. This insight will certainly be helpful as I think about owing my first home in the future. Further, we performed a linear regression to arrive at the Zestimate (Zillow's estimate for the fair value of the house). While the model wasn't very accurate due to its reliance on one type of data only, I enjoyed learning about how these tools can be used to perform interesting analysis, including some for my personal use

#Problem Description


The real estate market is something that every person living in the country has to deal with, and as a result it makes a great topic about data analytics. The housing price or rental price in San Francisco Bay Area accelerating at shocking rates. From 2010 to 2017, the median price of a single family home in San Francisco has gone from approximately &775,000 to $1.5 million
This project was aimed at collecting real estate data from The zillow website by web scraping and doing visualization and analysis on this data.

#Python Libraries used:

 BeautifulSoup (for scraping)
 Seaborn
 matplotlib
 RE

#Web scraping:

Data was collected for various California counties by scraping the zillow website for sold houses and new listings. The type of data collected includes the basic data of the house (beds, baths, area, price, etc) and some advanced data as well like type of property, schools in the area, walking and biking convenience, etc.

This data was then cleaned to make it ready for analysis. Redundant data was removed. Missing data was treated properly.

#Analysis:

Seaborn and matplotlib were used to do visualization of the data. The visualization gave some very good information about the trends we see with respect to the type of property. For instance, Palo Alto was expensive. But the more interesting observation was that the price difference between a 2br and a 3br house is not so much different. we also see that Townhouses are very famous in the bay area, especially San Francisco. This is because there is not enough land available there to build new houses.

There was other analysis done as well using property type and other fields.




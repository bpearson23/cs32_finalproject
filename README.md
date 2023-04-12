# cs32_finalproject

I am completing the final project independently.

## Tracking Historic Transaction Data on Whiskey Auctioneer:
The code in this project scrapes data on transactions from whiskeyauctioneer.com and collects the scraped data in a dataframe. It can be run iteratively to add any new completed transactions to the dataframe. Then, I take this data and track price trends over time for each whiskey expression in an attempt to identify how current prices compare to historic trends. 

## Motivation:
Connoisseurs of particular goods (especially luxury goods and alcohol) do many transactions through auction websites. There is a huge advantage to possessing the most updated information related to market prices versus historic prices and at what price transactions are usually taking place. The goal of this project is to create a dynamic data structure that keeps track of these changes to reduce the amount of time people have to go through these websites manually. 

## Build status: 
Based on the recommendation of a whiskey expert, I have decided to focus on whiskeyauctioneer.com. I have written two functions: one that does an initial scraping of the entire website and one that will be used in the future when people want to update the dataframe to reflect the most recent information. This initial scraper will take a long time to run so I have not run the whole thing in its entirety yet. 


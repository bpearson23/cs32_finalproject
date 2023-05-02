# cs32_finalproject

I am completing the final project independently.

## Tracking Historic Transaction Data on Whiskey Auctioneer:
The code in this project scrapes data on transactions from whiskeyauctioneer.com and collects the scraped data in a dataframe. It can be run iteratively to add any new completed transactions to the dataframe. Then, the user can filter the dataframe to look only at the whiskey expressions he or she is interested in. There are a series of filters available to the user such as name, distillery, price, etc, and the code will continue to ask for filters until the user is done filtering. The output is an interactive graph which show th price of the whiskey over time. It has hovering annotations that show the name, price, lot number, and auction date. 

## Motivation:
Connoisseurs of particular goods (especially luxury goods and alcohol) do many transactions through auction websites. There is a huge advantage to possessing the most updated information related to market prices versus historic prices and at what price transactions are usually taking place. The goal of this project is to create a dynamic data structure that keeps track of these changes to reduce the amount of time people have to go through these websites manually. 

## Functionality:

og_scraper is designed to be run once in order to scrape all historic data from the auction website. Then, the user can run scraper whenever there is new data added to the website, which will add rows to the dataframe until it finds a lot that is already in the dataframe and the function will stop running. search_scraper is a little bit different and will scrape particular lots based on a search term. It is not currently in full functioning form and is not part of the main project.  

Then, the output allows the user to filter based on 13 different types of parameters. The resulting dataframe is graphed in plotly to show price over time. 

## Build status: 
Based on the recommendation of a whiskey expert, I decided to focus on whiskeyauctioneer.com. I wrote three scraping functions: one that does an initial scraping of the entire website, another that will be used in the future when people want to update the dataframe to reflect the most recent information, and a final one that can be used to scrape based on a specific search term. I have not had time to run the initial scraper long enough to get all historical data, but have scraped about 14,000 rows in total. 

After scraping, I cleaned the data to make sure I could manipulate it in the right ways. Then, I created an iterative filtering section which allows the user to filter the dataframe according to the types of whiskey he or she is interested in. It will continue to ask for filtering criteria until the user is done, at which point a graph is produced that looks at the price of the whiskey over time according to the particular search filters. 

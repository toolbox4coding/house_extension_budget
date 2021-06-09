# House extension budget 
This is budget optimizer for house improvement project based on local house valuations. This program aims to find the optimal home improvement project (cost, additonal sq ft, rooms, bathroom etc...) to get a return of 1 (or lower). (Every Dollar spent is recognized in the market valuation)
On the tech side it's using supervise learning (gradient boosting) and coded in python
Data source area google spreadsheet where local / recent (off MLS) can be added and the selection of house to include be set
1. House closing price (or raw land is the house get turned down) based local completed sale less than 1 year near the property from Redfin (and later Zillow) 1 off mamual
2. Listing price for on the market properties

Data output is simple email to me with a table of options

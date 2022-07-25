# easytravel

Easytravel try to provide a better travel experience to tourists.

## background

Currently, covid is eased in many areas of US and europe. However, the airtravel and car rental prices shot very high. Many airlines are overbooked.
The covid guidelines in different area are different and are changing quickly.

All the above can be a headache to the travelers.

As many companies are now offering work remotely, we expect more travel in both business and leisure.

Easytravel try to promote a better travel experience for all.

## objectives

- find deals for air, car and hotels
- find information for destination for entertainment, like day trips etc.
- travel organizer. record the travel booking information, trip planning with different stops, etc.

## System Overview

Easy travel will have a user portal, it allows users to login, find deals, create trips and manage trips.

- User Portal: this is a typical flask web application
- deals: we need do data collection and store them in databases for query

### data collection
travel data, such as airline prices or hotel, rental car. can be obtained in two ways,
- use a commercial web API. basically you subscribe to a service and get a data feed. Some maybe free, but most will have a cost
- use a web crawler to grap data from web.
- Other alternatives ???

TODO:
- research different [travel APIs](https://rapidapi.com/blog/best-travel-apis-guide/) and find one to use. 
- research web scrapy technology and find a good tool to use. one such tool is called [scrapy](https://docs.scrapy.org/en/latest) 


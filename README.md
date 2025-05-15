# Cryptic

[Link to Github Cryptic Backend](https://github.com/logan-taggart/Cryptic-Back)


## Description:

Cryptic is a web application that allows users to search and find the latest information and statistics for the cryptocurrency of their choosing. Users are also able to save a cryptocurrency to their watchlist where they can later view the statistics of the cryptocurrency at the time that it was added to their personal watchlist. From there, Cryptic users can sort their watchlist in two ways. One, they can sort by alphabetical order, date added, or statistical data such as: price, market cap, and volume. Two, they can choose if they would like their watchlist presented in an ascending order or a descending order. In addition, users are able to view information on their Cryptic account through the profile page where they can view the username, email, and first and last name that are associated with the account.


## Features:

* **Account System:** <br />
	* I wanted to make a personalized experience for each specific user and to be able to implement some of the features that are listed below, I determined an account system was the best method for this project. <br />

* **Searchbar for Cryptocurrency Information:** <br />
	* This is the backbone of the application that allows users to find information on the different cryptocurrencies.

* **Dropdown Input to choose Fiat Currency that Cryptocurrency Statistics will be converted to:** <br />
	* I also wanted to make Cryptic an application that many people could use, so I added the option for a user to change the conversion currency between the globe's top 20 fiat currencies.

* **Watchlist System:** <br />
	* I built Cryptic to be a tool that cryptocurrency investors could use, and this expands upon that concept. I wanted to add a way for users to view the trends of many cryptocurrencies and some of the historical data for those cryptocurrency projects.

* **Sorting Form to Sort A User's Watchlist Data:**
	* I knew that a watchlist could get very long and cluttered, so I wanted to add an organizational tool that would allow a user to sort their list by a number of different metrics.

## User Flow:

The user will either be presented with the option to go to the sign in or create account page if they are not logged in or signed up, or a home page if they are signed in where they can search for information on a cryptocurrency and add it to their watchlist, or they can go to their account information page or watchlist where they can then sort the list by a few different metrics.


## API Used:

[CoinMarketCap API](https://coinmarketcap.com/api/) <br />
***The CoinMarketCap API limits the number of requests made to their API to 333 per day.***


## Tech Stack Used:

* Javascript
* NodeJS
* Express
* React
* React Router
* SQL
* PostgreSQL
* CSS
* Bootstrap

## Future Development Plans:

1. Add a button to remove cryptocurrencies from a user's watchlist.
2. Create a button on each cryptocurrency in a watchlist to get updated information and statistics on the selected cryptocurrency.
3. Add a profile edit form to allow a user to make changes to the information that is linked to their account.
4. Resolve bug that is causing application to not work properly in Safari.

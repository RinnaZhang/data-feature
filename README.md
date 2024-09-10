# assignment 1 | data-feature
This project combines real time exchange rates with relevant financial news to provide users with insights into the FX markets. 
I used two APIs: Currency Beacon API that fetches exchange rates and Currents API that retrieves related news.

Main program flow:
First, we fetch valid currencies and exchange rate data.
Then, the user inputs a base and target currency, and we return the exchange rate.
Next, we use the selected currency pair to retrieve relevant news articles from the Currents API.
Finally, we print the news articles or handle the case where no news is found.

If you want to learn more or use the program, please refer to the Google Colab file uploaded in this repository.

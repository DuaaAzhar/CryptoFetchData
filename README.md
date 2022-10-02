=> Fetch Crypto Data
Let us assume you are a crypto investor. You have made transactions over a period of time which is logged in a CSV file. Write a command line program that does the following

Given no parameters, return the latest portfolio value per token in USD
Given a token, return the latest portfolio value for that token in USD
Given a date, return the portfolio value per token in USD on that date
Given a date and a token, return the portfolio value of that token in USD on that date
The CSV file has the following columns

timestamp: Integer number of seconds since the Epoch
transaction_type: Either a DEPOSIT or a WITHDRAWAL
token: The token symbol
amount: The amount transacted
Portfolio means the balance of the token where you need to add deposits and subtract withdrawals. You may obtain the exchange rates from cryptocompare where the API is free. You should write it in Node.js as our main stack is in Javascript/Typescript and we need to assess your proficiency.


.........................................................................
 Instructions, to run the command line program, install the below dependencies

 npm install request 
 npm install promise
 npm install parser
 npm install await
 npm install yargs



Given a date and a token, return the portfolio value of that token in USD on that date
node fetchCyptoData.js --date=4/3/2019 --token=BTC

Given a date, return the portfolio value per token in USD on that date
node fetchCyptoData.js --date=4/3/2019


Given a token, return the latest portfolio value for that token in USD
node fetchhCyptoData.js --token=ETH

Given no parameters, return the latest portfolio value per token in USD
node fetchCyptoData.js

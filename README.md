# Problem

LoftBot our self driving robot has aquired a taste for beer. LoftBot is plannig a vaction to Washington State and would like to compile a list of breweries to visit. After a quick search we found a website we could use to compile our list: [Open Brewery Database](https://www.openbrewerydb.org/documentation/01-listbreweries)

The LoftBotOS can only consume JSON::API data and will be offline except for this local rails service which can be accessed on LoftBots LAN.

### Task #1
Create a postgresql database table `breweries` and rails model to store the list of breweries for washington state.

### Task #2
Create a service to populate our breweries table for Washington State only. Ensure the service is idempotent and will not create duplicate data.  Create a rake task that will call the service and run it.

### Task #3
Expose an API Endpoint for LoftBot to connect and consume the list of breweries.  LoftBot has very limited memory so we recommend only displaying 5 breweries at a time.

### Task #4
Filter results based on state and narrow the results based on location.

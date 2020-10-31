# Flight-Saver
Project1 Group5
A travel app designed to help plan your next trip by giving you quotes on available flights, currency exchange information, the current weather forecast for the destination, and the ability to save flights for later.

## Links
Deployment: https://apemint.github.io/Flight-Saver/
Repo: https://github.com/apemint/Flight-Saver

## Technologies
We mainly wrote our script code in Javascript, using jQuery.
Our pages were primarily written in HTML.
And Styling was primarily in Materialize with a secondary CSS style sheet.

## How to Use?
Simply input your departure city, choose an airport from the drop down, then input your destination city and choose the arrival airport. Click on 'from' and 'to' to choose the start and end dates of your trip via the pop up calenders and click find flights to submit your selections. Scroll down the page, and you will see the updated flight, currency and weather information. Under flight information, you may click the save flight button to save its corresponding flight information, and you can access your saved flights by clicking on the saved flights butoon at the top left of the page.
Click on 'get exchange' button to get the current exchange rate for the destination and your home currency. Default is in USD, and the destination's currency.

## APIs Used
Algolia Places
Leaflet/Open Street Map
Currency Converter
SkyScanner
Open Weather Map

## Contributors/Team
### Front-end
Janae
Sam
Ernesto
### Back-end
Nick
Kyle
Andres(Me)

### About My Contribution
I mostly worked on the Weather part of the app. This included writing the ajax call function to pull the weather data from open weather map, and creating cards through javascript to dynamically display onto the page when the search is made. Also used a unix timestamp to date function that made displaying the date of each forecast easier. Along with the weather part of the app, I assisted in ironing out bugs.

## Future Development
### Historical Weather Data
Currently, due to api limitations, we can only display a 5 day current weather forecast, which is not helpful if you are planning a trip in the far future. We would like to have implemented the historical weather data api from open weather map to display the historical typical weather for a location depending on the date/time of year you would be planning to go there, unfortunately this is a premium feature. 

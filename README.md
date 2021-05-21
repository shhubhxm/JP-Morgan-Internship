# JP-Morgan-Internship
 
## Stock Price data
Interface with a stock price data feed and analysis of the data.

My Aim: I had to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

* Created the getRatio function, getDataPoint and main functions.

## Data Visualisation 
Using JP Morgan Chase's frameworks and tools Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization was prepared by me.

My Aim: Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code such that it now updates automatically by continuously requesting from the server application.

* In the client application, I observed that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-            entered into the table. The updatation of the application such that the table does not have duplicated entries.
* The react app to keep continuosly requesting data from the python server. The application is build in such a way that it continuously query the datafeed every        100ms when the 'Start Streaming' is clicked.
* The perspective configurations is added so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.

## Traders Dashboard
The Data is display visually for traders. I used perspective to create the chart for the trader’s dashboard.

My Aim: To use Perspective to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. Basically, I modified the existing live chart to be able to (1) track and display the ratio between the two stock prices (2) shows the historical upper and lower bounds of the stocks' ratio (3) and finally, shows 'alerts' whenever these bounds are crossed by the ratio.

* The Graph tracks the ratio between two stocks over time and NOT the two stocks’ top_ask_price over time.
* The graph also tracks the historical upper and lower bounds of the stocks' ratio.
* Trigger 'alerts' (i.e. draw red lines) on the graph whenever the bounds are crossed by the calculated ratio in a specific time period.

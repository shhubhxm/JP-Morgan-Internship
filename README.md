# JP-Morgan-Internship
 
## Stock Price data
Interface with a stock price data feed and set up your system for analysis of the data

Aim: We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

1. Please clone this repository to start the task
2. Adjust the getRatio, getDataPoint and main functions
3. Bonus: Pass all unit tests and add more to cover edge cases
4. Upload a git patch file as the submission to this task

## Data Visualisation 
Use JP Morgan Chase's frameworks and tools Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization

Aim:Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application

1. Please clone this repository to start the task
2. [goal-a] In the client application, observe that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-      entered into the table. Update the application so that the table does not have duplicated entries
3. [goal-b] We also want the react app to keep continuosly requesting data from the python server. Currently, the data feed is called only once every time the 'Start    Streaming' button is clicked. Change the application to continuously query the datafeed every 100ms when the 'Start Streaming' is clicked.
4. [goal-c] Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded,    it shows the historical data of ask_price ABC in the Y line chart.
5. Upload a git patch file as the submission to this task

## Traders Dashboard
Display data visually for traders. Use Perspective to create the chart for the trader’s dashboard.

Aim: Use Perspective to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. Basically, you have to modify the existing live chart to be able to (1) track and display the ratio between the two stock prices (2) show the historical upper and lower bounds of the stocks' ratio (3) and finally, show 'alerts' whenever these bounds are crossed by the ratio.

1. Please clone this repository to start the task
2. From the existing live graph, update it to track the ratio between two stocks over time and NOT the two stocks’ top_ask_price over time.
3. Update the graph to also track the historical upper and lower bounds of the stocks' ratio
4. Trigger 'alerts' (i.e. draw red lines) on the graph whenever the bounds are crossed by the calculated ratio in a specific time period
5. Upload a git patch file as the submission to this task
6. Upload a video detailing your process and work

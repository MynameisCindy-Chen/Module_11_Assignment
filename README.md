# Module_11_Assignment

This assignment is using time series method and Prohet model to analyze and make a prediction based on the data from MercadoLibre google trend, stock price and sales amount.


Part 1 is to clean MercadoLibre search trend data then graph the trend.

Part 2 is to pull and clean stock data, graph the closed price by date. Then I combined both google trend and stock price into a dataframe. After that, I made a line graph to illustrate the difference.

I also include some calculations and add them to the dataframe, lagged search trends, stock volatility and hourly stock return. Then I calculate the correlation to see if there are any relationship or impact between search trends and stock price.

Since I have combined dataframe that collect enough data, I use prophet model to make a prediction for next 80 days, illustrate some graph to generate overall picture of performance on MercadoLibre.

Part 3 optional section is to pull and clean sales data, I also use prophet model to predict next 90 days sales/revenue, sum the total of sales based on best case, worst case and most likely case for next 90 days prediction.

Overall, I get a conclusion that the best case sales amount is \$1052.15, worst case sales amount is \$887.17, most likely sales amount is \$969.61

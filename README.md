# 3-Moving-averages-trading-strategy-testing

It is one of the most common trading stretagies.

In this we are going to analyze the movement of share price with the help of 3 different moving averages of different spans.

First we are loading the historical data into notebook. Then creating 3 different moving averages.

Then we are plotting moving averages with Adj Close price on the same grapg to visualize the movement

After that we are creating a function to determine when to buy and when to sell. We can use the graph plotted above to determine the relationship.

We are also trying to incorporate the picks as they are very good times to sell.

we are using buy list and sell list to append the Adj Close price at which we are buying and selling

Now we are going to plot Adj Close price with the buy list and sell list to visualize the time and amount at which we are buying and selling.

Finally we are calculating the profit that you can gain via following this strategy and simply buying at the starting point and selling at the end.

# In this Strategy we are making few assumptions which are

you can not short sell

you need to buy and sell same amount of shares all the time.

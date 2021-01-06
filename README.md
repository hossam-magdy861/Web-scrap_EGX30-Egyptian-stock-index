# Web-scrap_EGX30-Egyptian-stock-index
The code is web scarping url 'https://english.mubasher.info/countries/eg' that monitor EGX30 stock index

Note: the code should run after Egyptian market stock working hours to get the final close value for the index

Variable definitions:

1- soup: output after html parsing.

2- data: finding the target data in text (stock index values)

3- egx: data after spliting

4- close: is the closing stock price (in EGP).

5- prev_close: is the previous closing price on the day before.

6- change: difference between closing today's price with the previous closing price (in %).

7- volume: Stock Volume is a number of shares traded over specified period of time.

8- turnover: amount of money traded over specified period of time.

9- trades_num: number of trades dealed in a specified period of time.

EGX_Stock.db": database file saves the output

'egx_stock.txt': text file saves the ouput

# base111vb
Monitoring High Gas Price Outliers
for tx in block.transactions:
    if tx["gasPrice"] > w3.eth.gas_price * 2:
        print("Gas outlier")

# Fintech_finder

## object

Assumed the role of a Deveolper for Blockchain. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. Use the _Ethereum Blockchain network_ into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

# Step One Import Ethereum Transaction Functions into the Fintech Finder Application

Imported funtions that will be used on from the _cyrpto Wallet.py_ file, those functions which contains code for Fintech Finder’s customer interface, in order to add wallet operations to the application are imported with a simple **import _filename_** keep in mind that the files have to be in the same _Repository_ in order to have the files imported.

## cryptoWallet.py

The script in this _.py_ file conatin all the functions needed to have the _ethereum tranactions_. Listed are the functions contained in the _.py_file.

- Wallet
- wallet.derive_account
- get_balance
- fromWei
- estimateGas
- sendTransaction

To test the functions capabilites I have used a envrioment through _Ganache_, User has to create a **Mneonic Seed** variable that conatains the _seed Phrase_ that needs to be saved to a _.env_ function.

The next step which I used the _Steamlit_ library for user interface in the _fintech_finder.py_ file. To have the Account Holders **Ethereum address** and to display _account balance_.

# step Two Sign and Execute a Payment Transaction

I will write code that uses the calculated wage value to send a transaction that pays the worker. This code should allow the Fintech Finder customer to authorize the transaction with their _digital signature_. For the purpose of testing out this application, I will use your own **Ethereum account** information from _Ganache_  as the customer account information.

Since the application can now calculate the _Wage_ of the Fintech specialist I write the code that will allow a customer (Myself) to send an Ethereum blockchain transaction that pays the hired candidate and return a _validated Hash_.
![screen shot](Screen Shot 2022-07-21 at 8.43.20 PM.png)
# Step Three Inspect the Transaction

Now it's time to put it all together and test the Fintech Finder application with your newly integrated Ethereum wallet. You will send a test transaction by using the application’s web interface

- From your terminal, navigate to the folder that contains your .env file and the fintech_finder.py and crypto_wallet.py files.
- To launch the Streamlit application, type streamlit run fintech_finder.py in the terminal.
- On the resulting webpage, select a candidate that you would like to hire from the appropriate drop-down menu. Then, enter the number of hours that you would like to hire them for.
- Click the Send Transaction button to sign and send the transaction with your Ethereum account information.

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


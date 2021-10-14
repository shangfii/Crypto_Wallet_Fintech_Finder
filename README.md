# Crypto_Wallet_Fintech_Finder
Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them

# Table of Contents

[Project overview](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/README.md#project-overview)

[Technologies](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder#technologies-required) 

[Installation Guide](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder#installations)

[Demonstrations](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder#demonstrations) 


[Conclution](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder#conclusion)

[License](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/LICENSE)


# Project overview


This streamlit application called Fintech Finder created in the project helps to hire a fintech professional and pay them with ether using the user's crypto wallet. This is achieved by integrating the Ethereum blockchain network into the application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

# Technologies Required 

1. Python version 3.8.5: This project leveraes Python and specifically the following packages and modules:

a). Pandas - version 1.3.2 - For easy manipulation dataframes and create dataframes.

b). Streamlit - version 0.84.2 - To view the application into a web browser and for users interaction with the ledger.

c). Data Classes -Provides a decorator and functions for automatically adding generated special methods to classes

d).  datetime -  used this to be able to determine the UTC timezoon to create a time stamp in our blockchain.

e). typing-  allows for use of fundamental support consisting of the types Any, Union, Tuple, Callable, TypeVar, and Generic.

f). hashlib-  SHA256 was used to return a hexdigest.

g.) web3.py -  Python library for connecting to and performing operations on Ethereum-based blockchains.

h). eth-tester - Python library that provides access to the tools used to test Ethereum-based applications.

i). mnemonic - Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

j). bip44 - Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

k). Infura API - API grants access to the Ethereum network over HTTPS and account is required 

# Installations

Pip install the following applications and make sure they work properly:

* Make sure Python is installed and then start the follow installations 
* pip install streamlit
* pip install web3==5.17
* pip install eth-tester==0.5.0b3 or pip install eth-tester
*  pip install mnemonic
*  pip install bip44

# Demonstrations:

Use VScode to open and lauch the Fintech_finder.py file( see the image below for the launch area)

![streamlit launched ](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/Streamlit_app_launch.png)

When streamlit opens; the left site should look like the image below(Streamlit ready for transaction)

![streamlit ready for use](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/Streamlit_interacton_Fintech_finder.png)

When a transaction is done; the following image shows what you will see 

![Transaction done](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/transactions_done.png)

A scan of the senders wallet on the Kovan testnet (Sender's Kovan scan)

![Sender's Kovan scan](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/Sender_Kovanscan.png)

Recipient's address scan on the Kovan tesnet (Recipient's address scan)

![Recipient's Kovan scan](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/recipient_got_it.png)

Transaction block Scan info 

![Transaction block scan](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/transaction_block.png)

Recipients transaction details 

![Recipients transacton scan](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/recipient_transaction_details.png)

wallet scan of recipient 

![wallet scan of recipient](https://github.com/shangfii/Crypto_Wallet_Fintech_Finder/blob/main/Fintech_finder/Images/recipient_got_it.png)

# Conclusion:

Overall the project is a success, The images above show that a Fintech profesional can be hired and paid directly from the streamlit application and the transacton visible on the scan. Although this used the testnet, it can be intergrated and used in the mainnet to functoin as illustrated here. 

This application could be improved by adding a link to the proffessional's resume and developement background page. Hiring a professional requires more to consider than what we have here.





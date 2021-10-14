# Crypto_Wallet_Fintech_Finder
Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them

Table of Contents

Project overview

Technologies 

Installation Guide

Demonstrations 

Usage


License


# Project overview


This streamlit application called Fintech Finder created in the project helps to hire a fintech professional and pay them with ether using the user's crypto wallet. This is achieved by integrating the Ethereum blockchain network into the application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

# Technologies Required 

1. Python version 3.8.5: This project leveraes Python and specifically the following packages and modules:

a). Pandas - version 1.3.2 - This was used to be able to easily manipulate dataframes and create dataframes.

b). Streamlit - version 0.84.2 - To be able to view the application into a web browser and that users can interact with the ledger.

c). Data Classes -This module provides a decorator and functions for automatically adding generated special methods to classes, which managed us to use class blocks into our code structure.

d).  datetime - While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation. In our case, we used this to be able to determine the UTC timezoon to create a time stamp in our blockchain.

e). typing- This allows us to use the most fundamental support consisting of the types Any, Union, Tuple, Callable, TypeVar, and Generic.

f). hashlib- This module implements a common interface to many different secure hash and message digest algorithms. In our application, we use SHA256 to return a hexdigest.

g.) web3.py - This is a Python library for connecting to and performing operations on Ethereum-based blockchains.

h). eth-tester - This is a Python library that provides access to the tools we’ll use to test Ethereum-based applications.

i). mnemonic - This is a Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

j). bip44 - This is a Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

k). Infura API - An API that provides instant access to the Ethereum network over HTTPS (i.e., the web). You will need to create an account with Infura.

# Installations

Pip install the following applications and make sure they work properly:


. pip install streamlit

. pip install web3==5.17

. pip install eth-tester==0.5.0b3 or pip install eth-tester

. pip install mnemonic

. pip install bip44

# Demonstrations:

Use VScode to open and lauch the Fintech_finder.py file 


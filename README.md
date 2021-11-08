# ETHEREUM WALLET APP - FINTECH TALENT FINDER
**For Hiring FinTech Professionals**

**BACKGROUND:** As Fintech Finder’s Lead Developer, I need to build a front-end web application (Streamlit) integrated with Ethereum Blockchain Network in order to enable our customers to instantly pay the FinTech Professionals whom they hire with Ethereum Crypto. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CONTENT**
- Project Description
- Technologies
- Blockchain Web-Application
- Contributor
- License
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**PROJECT DESCRIPTION**

There are 2 major sections defined for this whole project: 

**A. Wallet Functionality:** 

Following functions are defined under crypto_wallets (Wallet Functionality):

**1. generate_account():** Purpose: Create a Digital Wallet & Ethereum Account from a mnemonic seed phrase.
 
 **- Define Variables: Mnemonic & Wallet:** Create Wallet with the help of unique combination of mnemonic seed phrase.
 
 **- Derive Keys:** Using "derive_account" function to generate Private & Public Keys.
 
 **- Convert into Ethereum Account:** Using Private Key to convert it into the Ethereum Account.
 
 **2. get_balance(address):** Purpose: Using an Ethereum Account address to access the balance of Ether

**- fromWei:** Convert Wei value to Ether.

**3. send_transaction(account, to, wage):** Purpose: Send an authorized transaction to the Kovan testnet.

**- setGasPriceStrategy:** Apply this function to set the gas price strategy.

**- toWei:** Convert eth amount to Wei.

**- estimateGas:** Calculate estimated gas required for transaction with parameters: ({"to": to, "from": account.address, "value": value})

**- Sign & Send Transaction:** Sign the Raw Transaction & Send it to the receiver. 


**B. FinTech Finder App Functionality:**

Following functions are defined under FinTech Finder App Functionality:

**1. candidate_database:** Database of FinTech Finder candidates including: Name, Ethereum Wallet Address, Rating & Ether Rate/Hr.

**2. get_people():** Display the database of Fintech Finders candidate information.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**TECHNOLOGIES**
- Python
- Web3.py
- Kovan Testnet 
- Ethereum
- Streamlit
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**BLOCKCHAIN WEB APPLICATION**
------------------------------

****



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CONTRIBUTOR**

- PRATEEK SHARMA

www.linkedin.com/in/prateek-sharma-21a081180

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**LICENSE**

GNU General Public License v3.0

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

There are 4 FinTech Professionals listed on the front-end web app to choose from:
![Fintech Finder Hompage1](https://user-images.githubusercontent.com/86034323/140715745-71118a10-c7ec-4109-852a-f24d3bc07c01.png)
![Fintech Finder Hompage2](https://user-images.githubusercontent.com/86034323/140715782-bb5b332c-dc01-4436-927c-5e279d478ee2.png)
![Fintech Finder Hompage3](https://user-images.githubusercontent.com/86034323/140715803-26e9adc8-e8a0-47a1-82ea-ee4a4aaa89ed.png)





--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CONTRIBUTOR**

- PRATEEK SHARMA

www.linkedin.com/in/prateek-sharma-21a081180

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**LICENSE**

GNU General Public License v3.0

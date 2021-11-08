# FINTECH TALENT FINDER APP - ETHEREUM WALLET
**For Hiring FinTech Professionals**

**BACKGROUND:** As Fintech Finder’s Lead Developer, I need to build a front-end web application (Streamlit) integrated with Ethereum Blockchain Network in order to enable our customers to instantly pay the FinTech Professionals whom they hire with Ethereum Crypto. 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CONTENT**
- Project Description
- Technologies
- Streamlit App Integrated with Ethereum Blockchain Network
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
**STREAMLIT APP INTEGRATED WITH ETHEREUM BLOCKCHAIN NETWORK**
------------------------------

**1. Homepage view with FinTech Professionals' details:** 

There are 4 FinTech Professionals listed on the front-end web app to choose from:

![Lane](https://user-images.githubusercontent.com/86034323/140721698-0a59b19a-105e-4b3e-bc76-036219127e37.png)
![ash](https://user-images.githubusercontent.com/86034323/140721732-9d0baa72-54b1-4597-8095-64c7269df347.png)
![Jo](https://user-images.githubusercontent.com/86034323/140721760-bec9b68e-06be-4535-9891-a70213b776e6.png)
![Kendall](https://user-images.githubusercontent.com/86034323/140722093-fb2a4aea-0ba4-444b-91c2-3860fae4a928.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**2. List of Values (LOVs) to pick & hire the desired professional to get paid in Ether:**

There's a List of Value (LOVs) drop down window feature available to choose the desired professional to hire and get paid in Ether:

![LOVs](https://user-images.githubusercontent.com/86034323/140716741-0aa492be-2814-406d-9750-53d11f2fc243.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**3. Select Candidate: "Kendall" & Pay Compensation in Ether:**

Select the desired candidate, in this example we chose "Kendall" and paid him in Ether:

![TRX_1](https://user-images.githubusercontent.com/86034323/140717174-72f61d72-a656-470f-9f75-e69d12ccb2c9.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**4. Transaction Validation:**

Transaction can be validated by referring the transaction hash available right after processing the payment:

![TRX_1_Validated_ Hash](https://user-images.githubusercontent.com/86034323/140717630-cc1d3839-958e-4c61-b3e2-00a92bdafeb4.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**5. Verify the Business Account Transaction:**

Transaction can be verified on Etherscan (Ethereum's Kovan Testnet) for company's account balance:

![Address_balance_with_transactions_history](https://user-images.githubusercontent.com/86034323/140720060-8d0dd638-7d87-440a-8051-c26ab936103e.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**6. Verify the Transaction Details:**

Transaction details can be verified on Etherscan (Ethereum's Kovan Testnet) by clicking on transaction hash:

![Transaction_details_etherscan](https://user-images.githubusercontent.com/86034323/140720482-486e4a55-697b-4605-b04c-790c56a40e61.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**7. Verify the Receiver's Account Transaction:**

Transaction can be verified on Etherscan (Ethereum's Kovan Testnet) for receiver's account balance:

![Kendall_Balance_with_TRX_History](https://user-images.githubusercontent.com/86034323/140719675-259a3b40-5e9c-4163-82cc-cbe974ece8e6.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**CONTRIBUTOR**

- PRATEEK SHARMA

www.linkedin.com/in/prateek-sharma-21a081180

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**LICENSE**

GNU General Public License v3.0

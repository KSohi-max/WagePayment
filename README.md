# Wage Payment

This code enables users/customers to send cryptocurrency payments to professionals for completed work. A Streamlit UI is used to complete the transaction.
<br />
<br />
### Steps Completed

* Generated a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.
* Fetched and displayed the account balance associated with Ethereum account address.
* Calculated the total value of an Ethereum transaction, including the gas estimate, that pays a professional candidate for their work.
* Digitally signed a transaction that pays a professional candidate, and send this transaction to the Ganache blockchain.
* Reviewed the transaction hash code associated with the validated blockchain transaction.
<br />

### Completed Transaction Results

On the Streamlit webpage, a professional candidate is to be selected from the drop-down menu.  The number of hours that they are to work is entered. Send Transaction button is clicked to validate the transaction.
<br />
<br />
#### Wage Payment UI Video
Click Image to watch the Video

[![Wage Payment Video](https://github.com/KSohi-max/WagePayment/blob/main/Images/Streamlit%20Webpage.png)](https://youtu.be/Ya0N3q-9ZJE)
<br />
<br />
#### Ganache Transactions
Reviewing the transactions on Ganache, you can see that a total of 3 transactions were completed. 

![Ganache Transactions](https://github.com/KSohi-max/WagePayment/blob/main/Images/Ganache%20Transactions.png)
<br />
<br />
#### Ganache Transaction Details
Reviewing the transaction detail on Ganache, you can see the details including Sender, To addresses, Value, Gas Used, Gase Price, Gas Limit and Mined in Block.

![Ganache Transactions](https://github.com/KSohi-max/WagePayment/blob/main/Images/Transaction%20Details.png)

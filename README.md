# WagePayment

This code enables users to send cryptocurrency payments to professionals for completed work. A Streamlit UI is used to complete the transaction.

### Steps Completed

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.
* Fetch and display the account balance associated with your Ethereum account address.
* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a KryptoJobs2Go candidate for their work.
* Digitally sign a transaction that pays a KryptoJobs2Go candidate, and send this transaction to the Ganache blockchain.
* Review the transaction hash code associated with the validated blockchain transaction

### Completed Transaction Results

On the Streamlit webpage, a professional candidate is to be selected from the drop-down menu.  The number of hours that they are to work is entered. Send Transaction button is clicked to validate the transaction.

Click to watch the Video

[![Wage Payment Video](https://github.com/KSohi-max/WagePayment/blob/main/Images/Streamlit%20Webpage.png)](https://youtu.be/Ya0N3q-9ZJE)

Reviewing the transactions on Ganache, you can see that a total of 3 transactions were completed. 

![Ganache Transactions](https://github.com/KSohi-max/WagePayment/blob/main/Images/Ganache%20Transactions.png)

Reviewing the transaction detail on Ganache, you can see the details including Sender, To addresses, Value, Gas Used, Gase Price, Gas Limit and Mined in Block.

![Ganache Transactions](https://github.com/KSohi-max/WagePayment/blob/main/Images/Transaction%20Details.png)

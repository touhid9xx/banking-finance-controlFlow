# Control Flow for Transaction Logic

* Use Python control flow to handle banking transactions.

* Control flow helps ensure rules are followed, like flagging large withdrawals and preventing fraudulent activity.
* You will work with real-world-style synthetic transaction data.

* By the end, you will write logic to detect suspicious transactions, approve or reject transfers, and summarize customer activity.

# Banking transactions data Description:

* The dataset represents real-world-like banking transactions.

* Each row is a transaction involving a customer.

* Important columns are: transaction_id, customer_id, amount, transaction_type, channel, date.

* Check if amounts are negative or miss if the type is 'Credit' or 'Debit'.

* Create synthetic data 

# Basic if statement for transaction rules

* Control flow is used to separate 'Debit' and 'Credit' logic.

* Flag transactions above a certain amount.


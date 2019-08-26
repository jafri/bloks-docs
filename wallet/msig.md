# MSIG

## HOW TO CREATE AN MSIG

### 1. Check that you are logged in to Bloks using one of the wallet options.

### 2. Select the dropdown menu from your account and toggle the Multisig Mode option.

![](../.gitbook/assets/image%20%28129%29.png)

### 3. Select **Wallet** on the top menu.

![](../.gitbook/assets/image%20%2839%29.png)

### 4. Transfer Token page should be the initial page under Wallet. We will demo a transfer transaction for this MSIG. 

![](../.gitbook/assets/image%20%281%29.png)

![](../.gitbook/assets/image%20%28131%29.png)

Fill out the 3 fields and click the Transfer button to complete transaction.

### 5. You will be taken to a new page to Propose Multisig Transaction.

![](../.gitbook/assets/image%20%283%29.png)

The Multisig page will have 4 fields to fill in;

* Proposer - The account you are proposing the multisig from.
* Proposal Name - Name of the proposal and can be 2-12 characters long.
* Requested Approvals - List which accounts can prove this transaction. These are accounts listed as authorizations.
  * Actor - Account name
  * Permission - Owner or Active
* Authorization
  * Actor
  * Permission

![](../.gitbook/assets/image%20%28111%29.png)

You will receive a Success message along with a transaction hash to check the completed action, as well as a link to check the proposal. You can share your MSIG with this link provided.

![](../.gitbook/assets/image%20%2872%29.png)

The link to the proposal will show the proposal in detail, with the Proposer, Proposal Name, Approval Status and the current Request Approvals by the account\(s\) and their individually status.

The Show Transaction button will show the action in code.

The Approve Transaction button is for anyone who is listed as a Requested Approval to Approve Transaction after review.

Execute Transaction 

### 6. Approve and execute your proposal by toggling off MSIG mode from the dropdown list on the right corner and signing in or sending the proposal link to the Account holder for approval.

If you are logged into an account that is listed as one of the Request Approvals, find the proposal and click Approve Transaction.



![](../.gitbook/assets/image%20%28127%29.png)

Once the Approval Status reaches the minimum threshold, you can now execute the transaction. Press Executive Transaction.

![](../.gitbook/assets/image%20%28104%29.png)

You will receive a Success message with a transaction hash attached. You can also search up the account and verify transaction to see if the transfer has been executed.



## Potential Errors

{% hint style="danger" %}
### Scatter users may receive an error "firewalled". This is because Scatter automatically Blacklists eosio.msig approve as an action.

You will need to open up Scatter, go to Settings, Firewall, and remove eosio.msig approve as a Blacklisted Action.
{% endhint %}

![](../.gitbook/assets/image%20%28113%29.png)


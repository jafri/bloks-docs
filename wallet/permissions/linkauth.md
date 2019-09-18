# Link Auth

Now that a new custom permission has been created \(previous guide\), you need to assign to the permission what it is allowed to do using Link Auth.

## HOW TO MAKE A LINK AUTH

### 1. Select **Wallet** on the top menu.

![](../../.gitbook/assets/image%20%2874%29.png)

### 2. Select Keys and Permissions ****from the left side menu.

![](../../.gitbook/assets/image%20%2861%29.png)

Click on the Link Auth tab.

It will show;

* Permission \(only needed for linking\) - This is the name of the permission you created from Add Custom Permission \(eg. In our case it was vote\). 
* Contract Name - Name of the contract \(eg. eosio\)
* Contract Action - Name of the action \(eg. claimrewards\)

{% hint style="info" %}
You can find a complete list of eosio contract actions at [EOSIO on Bloks.io, Contract, and Actions. ](https://bloks.io/account/eosio?loadContract=true&tab=Actions&account=eosio&scope=eosio&limit=100)
{% endhint %}

### 3. Fill in the 3 required blank fields and click Link Auth.

![](../../.gitbook/assets/image%20%28261%29.png)

Once all three required fields are filled out, check the bottom to see if the correct permission you want to link authorization to is highlighted with the contract name and contract action you've input. Click Link Auth to finalize transaction. 

![](../../.gitbook/assets/image%20%2821%29.png)

If you are using Scatter, you will need to click Allow action linkauth to proceed with this action.

![](../../.gitbook/assets/image%20%2819%29.png)

A success message will pop up with a transaction has to confirm you've completed Link Auth.




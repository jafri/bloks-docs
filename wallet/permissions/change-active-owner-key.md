# Change Active / Owner Key

An EOS account can have multiple keys associate with it. Each key allows a certain permission to the account it is attached to.

It is a recommended safety measure to create both an **Active** and **Owner Key** for your EOS account in the case that your Active Key becomes compromised as actions can be taken via your Owner Key to limit access to the hacker.

An **Owner Key** allows you Owner permission to your EOS account. As the name dictates, having the Owner Key means you have ownership of the account. There are very few transactions that require you to use your Owner Key and you should not be using it on a regular basis for daily transactions.

An **Active Key** allows you to set restricted permissions and can be used for transferring funds, voting, and making other account related changes. 

{% hint style="warning" %}
It is important for you to always keep your keys safe. Exposing your Owner Key may lead your account being compromised. Never share your Owner Key with anyone.
{% endhint %}

## HOW TO CHANGE ACTIVE/OWNER KEY

### 1. Select **Wallet** on the top menu.

![](../../.gitbook/assets/image%20%2847%29.png)

### 2. Select Keys and Permissions ****from the left side menu.

![](../../.gitbook/assets/image%20%2838%29.png)

The Keys and Permissions page displays 3 tabs;

* **Simple** - Displays what permission you are currently logged in with, what keys you are able to change, and a field to enter New Active Key
* **Advanced** - Allows you to Add New Permissions
* **Link Auth** - Shows fields for Permission \(only needed for linking\), Contract Name, Contract Action

If you are logged in with your Owner Key, you should see two fields; New Owner Key and New Active Key.

![When you are logged in with your Owner Key](../../.gitbook/assets/image%20%2879%29.png)

![When you are logged in with your Active Key](../../.gitbook/assets/image%20%28127%29.png)

### 3. Enter your New Active/Owner Key in the respective field. Click Change Permissions.

You can generate new keys by using various methods. The most secure method is to generate a key pairing while you are offline using EOSKEY.io and storing the private key offline where it is safe.

![](../../.gitbook/assets/image%20%2892%29.png)

Confirm that the New Active Key displays under the New Permissions tab identically. Click the Change Permissions button and confirm that the key has been changed when you receive a transaction hash with a Success message.

![](../../.gitbook/assets/image%20%2860%29.png)

## Potential Errors

{% hint style="danger" %}
### Scatter users may receive an error "firewalled". This is because Scatter automatically Blacklists updateauth as an action.

You will need to open up Scatter, go to Settings, Firewall, and remove updateauth as a Blacklisted Action.
{% endhint %}

![](../../.gitbook/assets/image%20%2883%29.png)

![](../../.gitbook/assets/image%20%28170%29.png)



![](../../.gitbook/assets/image%20%2887%29.png)






# Ledger

This quick guide will walk you through how to use your EOS account with a [Ledger Nano X ](https://shop.ledger.com/products/ledger-nano-x)or [Ledger Nano S.](https://shop.ledger.com/products/ledger-nano-s/) This allows you to use [Bloks.io](https://bloks.io/), the most comprehensive EOSIO Portal, with the added security of a hardware wallet from the convenience of your browser.

## LOGIN TO BLOKS.IO USING LEDGER S/X

### 1. Prepare Ledger S/X

Before you get started, make sure you have completed the following setup:

* Ledger is configured and powered on
* Ledger is firmware is updated and has the **EOS App** installed

If you haven’t completed these steps, [click here](https://support.ledger.com/hc/en-us/articles/360000613793-Set-up-as-new-device) before following along with this guide.

### 2. Log into Bloks.io with your Nano Ledger S/X. Select Ledger X or Ledger S as a sign-in option.

![](../../.gitbook/assets/image%20%2882%29.png)

Head to [Bloks.io](https://bloks.io/) and click on the Login Button on the top right-hand side of the page.

![](../../.gitbook/assets/image%20%2826%29.png)

Find **Ledger X or Ledger S** as a sign-in option and select it.

![](../../.gitbook/assets/image%20%2841%29.png)

Enter **“0,1,2"**, and select either USB or Bluetooth.

![](../../.gitbook/assets/image%20%28107%29.png)

If this is the first time using your Ledger, you will see a message similar to the image above stating there are “**No Accounts Found**”. This is to be expected. **Copy** one of the **public keys** displayed onto a notepad.

If you don’t have an EOS account, create one [here](https://bloks.io/wallet/create-account) with the key you copied, and proceed to **Step 4**.

If you already have an EOS account on another wallet such as Scatter, proceed to **Step 3**.

### 3. Log into your existing account.

![](../../.gitbook/assets/image%20%28144%29.png)

Head over to [Bloks Permission Manager.](https://bloks.io/wallet/permissions) Log into your existing EOS account using Scatter or another wallet. Make sure you log in with your **Owner Key**\(can change both Owner and Active\) or **Active Key** \(can only change Active\).

Paste your keys from Step 2 into the fields above and click **Change Permissions**. Take care to ensure the keys you paste are the same you copied in Step 2.

### 4. Login to Bloks.io with your Ledger S/X and it will show you your account.

![](../../.gitbook/assets/image%20%28116%29.png)

Repeat all the steps in Step 2. This time [Bloks.io](https://bloks.io/) should show you the accounts associated with your Ledger key.

### 5. Allow Contract Data. _\(Optional\)_

If you want to be able to interact with custom contracts on the EOS blockchain, you will need to turn on _Contract Data_ on your ledger device. To do this complete the following steps:

![](https://miro.medium.com/max/500/1*C_ZZd9nE9eNQKI0q1L247A.jpeg)![](https://miro.medium.com/max/500/1*cDP9gVPbafkkAYYbExQgxQ.jpeg)

* Open the EOS app on your Nano Ledger
* Scroll through and select **Settings**

![](https://miro.medium.com/max/500/1*uqoTCgU3NwzOZ-w4rwCQ3Q.jpeg)![](https://miro.medium.com/max/500/1*pFHCxHL6-kYvqXBcujfUxw.jpeg)

* Find the “**Contract Data**” setting \(the default setting should be **NOT Allowed\).**
* Use the buttons to change this setting to **Allowed.** You can now use your Ledger to complete custom contract action on EOS.


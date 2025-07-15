---
icon: person-hiking
cover: ../.gitbook/assets/photo_2025-01-30_13-58-19.jpg
coverY: 128.7415982076176
---

# MultiWallet BuyBot

**Command:** `/multiwallet_buy_bot`

### 💡 What is the MultiWallet BuyBot?

The **MultiWallet BuyBot** is built to buy or sell coins using up to **300 wallets**.\
You can fund, manage, and control all wallets from a single UI — making large-scale trades **easy, fast, and decentralized**.

***

### Available Pools

{% hint style="success" %}
<p align="center"><strong><code>PumpSwap, PumpFun, Raydium AMM, Raydium CPMM,</code></strong></p>

<p align="center"> <strong><code>Raydium CLMM, Raydium Launchpad,</code></strong></p>

<p align="center"> <strong><code>Meteora DLMM, DYN, DLMM2</code></strong></p>
{% endhint %}

{% hint style="warning" %}
**Every wallet needs to hold at least 0.1 SOL to perform as expected. Lower amount deposits can cause an errors and failing transactions.**&#x20;

<h4 align="center"></h4>

<h4 align="center"><strong>Bot is taking 2% fee from buy/sell transactions.</strong> </h4>
{% endhint %}

***

### ⚙️ Manage Projects

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
**Create Project**

New Project using CA, bot will ask for Pool Address to do a pre-setup.&#x20;
{% endstep %}

{% step %}
**Select Existing Project**

* If you already have a project, you can select it to get navigated project Screen
{% endstep %}
{% endstepper %}

### ⚙️ Manage Wallets&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2025-07-16 at 2.31.53 AM.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### Generate wallets if needed

Create and attach to project up to 300 Wallets.&#x20;
{% endstep %}

{% step %}
### **Send SOL to Wallets**

Distribute SOL across wallets for trading. You can choose between:

* **🔀 Random Distribution:**\
  Ideal for stealth buying — some wallets get more, others less. Makes activity look more organic.
* **⚖️ Equal Distribution:**\
  Distributes SOL evenly to all wallets — easier to track and control.

> ✅ Tip: Equal distribution is great for managing supply. Random is better for realism.

<figure><img src="../.gitbook/assets/Screenshot 2025-07-16 at 2.36.04 AM.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Get SOL from Wallets

Withdraw remaining SOL from generated wallets back to your **Main Wallet**.\
Note: **Transaction fees** are paid from your Main Wallet.
{% endstep %}

{% step %}
### Balances

View token and SOL balances inside the wallets.

> If there are more than 30 wallets, the bot will split the result across multiple messages.
{% endstep %}

{% step %}
### Export Wallets

Export private keys if needed.\
You have **full control** over all generated wallets.
{% endstep %}

{% step %}
### Withdraw Bot Wallet

Transfer any remaining **SOL** from the bot wallet back to your main account.
{% endstep %}
{% endstepper %}

### ⚙️ Trading Scene

<figure><img src="../.gitbook/assets/Screenshot 2025-07-16 at 2.43.56 AM.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
### **🕒  Txn Speed**

Control how fast the bot sends transactions. Choose between:

* **Stealth Mode:**\
  Sends transactions in different slots, making them harder to detect and avoiding bundling.\
  Ideal for flying under the radar.
* **Fast Mode:**\
  Sends all transactions as quickly as possible.\
  Good for instant activity, but easier to detect.
{% endstep %}

{% step %}
### 🛒 Buy from All Wallets

Triggers a buy from **all connected wallets** using the selected **transaction speed**.
{% endstep %}

{% step %}
### 📉 Sell % from All Wallets

Allows you to define a **percentage of tokens** to sell from all wallets.\
The bot will prompt you to input the sell ratio.

***
{% endstep %}
{% endstepper %}

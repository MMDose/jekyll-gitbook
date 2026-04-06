---
icon: bolt-auto
---

# Auto-Sell

## Auto Sell — (Take Profit & Stop Loss)

Auto Sell watches your position and sells automatically — no need to monitor the chart manually.

Set one or multiple TP and SL levels and Thor handles the rest. You can also choose between three sell modes to control exactly how your tokens are sold across multiple buys.

**Take Profit (TP)** — Triggers when the price hits your target gain. Example: +50% sells when the token is up 50% from your entry.

**Stop Loss (SL)** — Triggers when the price drops to your set threshold. Example: -30% sells if the token falls 30% from your entry.

***

### **Auto-Sell Modes – explained simply**

**Key rule for DCA & Position Mode**

Your sell % values must add up to exactly **100%**. Why? Because the coin amounts are calculated at the time of your buy.

Example: You buy 1,000 coins and set 10 orders at 50% each → Order 1 sells 500, Order 2 sells the remaining 500. Done.

Correct split:

* TP 50% → 500 coins
* TP 25% → 250 coins
* TP 10% → 100 coins
* TP 5% → 50 coins
* TP 5% → 50 coins
* **= 100% ✓**

### **The 3 Sell modes**

**By Position** _(Default)_ Every buy gets its own sell order. Each order only sells the tokens from that specific buy — nothing more.

Buy 1 SOL → gets 1,000 tokens → sells those 1,000 at +50% Buy 2 SOL → gets 2,000 tokens → sells those 2,000 at +50% Both orders run independently.

**Sell All** Sells a % of everything you hold at the moment the order triggers.

Buy 1 SOL → 1,000 tokens, then Buy 2 SOL → 2,000 tokens First order hits → sells all 3,000 tokens at once Second order has nothing left to sell.

**By Average** _(DCA)_ Instead of creating a new sell order for each buy, Thor updates the existing one. The trigger price shifts to your average entry.

Buy 1 SOL at $0.001 → TP set at $0.002 Buy again at $0.003 → Thor recalculates: avg entry $0.0015, new TP at $0.003 You still have one order — not two.

***

### **Setup**&#x20;

1. Go to **Settings**.

<div align="left"><figure><img src="../../.gitbook/assets/image (28) (3).png" alt="" width="395"><figcaption></figcaption></figure></div>

2. Click on **Trading Settings**.

<div align="left"><figure><img src="../../.gitbook/assets/image (31) (1).png" alt="" width="402"><figcaption></figcaption></figure></div>

3. Enable **Auto Sell** by toggling it on.

<div align="left"><figure><img src="../../.gitbook/assets/image (34).png" alt="" width="395"><figcaption></figcaption></figure></div>

4. Configure your sell mode, Take Profit & Stop Loss and slippage — then enable Auto Sell.

<div align="left"><figure><img src="../../.gitbook/assets/image (57).png" alt="" width="398"><figcaption></figcaption></figure></div>

{% hint style="info" %}
**Note:** Auto Sell rules only apply to new trades opened after enabling the feature — not to existing positions.
{% endhint %}

---
icon: person-hiking
cover: ../.gitbook/assets/photo_2025-01-30_13-58-19.jpg
coverY: 128.7415982076176
---

# Organic Volume Bot (Bundled)

**Command:** `/organic_volume`

### What is Bundled Organic Volume Bot?

The **Bundled Organic Volume Bot** is engineered to simulate natural trading activity by performing **4 randomized transactions simultaneously** in each bundle. Every transaction is crafted to create a fresh maker signature, helping avoid detection and mimic organic market behavior.

**How It Works:**

* 🔁 **Random Buy/Sell Combinations**: Each bundle contains 4 trades, with randomized sequences like:
  * 2 Sells → 2 Buys
  * 1 Buy → 3 Sells
  * 3 Buys → 1 Sell
  * and many other variations\
    The bot may end a cycle on buys or sells — just like a real trader.
* 📊 **Fresh Maker Each Time**: Every transaction creates a unique market-making footprint.
* 🎲 **Random Amounts & Holding**: Trade sizes and hold times are randomized to prevent patterns and push the chart upwards.
* 🟢 **Bullish Chart Behavior**: By timing buys to close candles green, the bot helps build upward pressure in a stealthy way.

This bot is perfect for teams aiming to drive volume organically while supporting bullish sentiment.

***

### Available Pools

{% hint style="success" %}
<p align="center"><strong><code>PumpSwap, Raydium AMM, Raydium CPMM, Raydium CLMM, Raydium Launchpad, Meteora DLMM, DYN, DLMM2</code></strong></p>
{% endhint %}

***

{% hint style="danger" %}
**Before starting the bot, set your contract address and whitelist it, then adjust the settings and hit start, then wait for buy sell performances from organic wallets.**&#x20;
{% endhint %}

***

### ⚙️ Available Controls

{% stepper %}
{% step %}
**Start / Stop**

Start the bot manually. Stop it anytime when not needed, and **resume it instantly** when you're ready again.
{% endstep %}

{% step %}
**Speed**

* Control how fast the bot sends transactions.
* Higher speed = more volume but faster balance consumption.
* Lower speed = more natural, slower burn.
{% endstep %}
{% endstepper %}

<div align="left" data-full-width="false"><figure><img src="../.gitbook/assets/Screenshot 2025-07-21 at 8.21.18 PM.png" alt="" width="375"><figcaption><p>Command /<code>organic_volume</code>, Organic Volume Bot Screen</p></figcaption></figure> <figure><img src="../.gitbook/assets/Screenshot 2025-07-21 at 8.21.45 PM.png" alt="" width="193"><figcaption></figcaption></figure></div>

### ✅ Bot Checklist:

1\. Set Token Contract Address&#x20;

2\. Adjust the Speed

* Deposit min amount to your wallet if needed.&#x20;

3\. Start the Organic Volume Bot




---
description: >-
  Thor’s Auto Sell feature lets you lock in profits or cut losses automatically
  — no need to watch the charts 24/7.
icon: bolt-auto
---

# Auto-Sell (TakeProfit/StopLoss)

## ⚡Auto Sell — Take Profit & Stop Loss

You can set multiple take-profit (TP) and stop-loss (SL) levels, or create precise limit sell orders based on either fixed token amounts or portfolio percentages.

***

### 🔱 Auto-Sell Take-Profit / Stop-Loss Set-up

**How it works:**

* **Take Profit (TP):** Automatically sells when price hits your target gain.\
  &#xNAN;_&#x45;xample: +50% means the bot sells when price rises by 50% above entry._
* **Stop Loss (SL):** Automatically sells when price drops to your chosen threshold.\
  &#xNAN;_&#x45;xample: -30% means your bag is protected if price falls 30%._

**Setup by using Auto Sell steps (pre set up):**\


1. Go to **Trading Settings** and enable **Auto Sell.**

<div align="left"><figure><img src="../../.gitbook/assets/image.png" alt="" width="344"><figcaption></figcaption></figure></div>

2\.  Create TP/SL rules.\


* Use negative % for stop loss (-50%), positive % for take profit (+50%).\
  \
  ![](<../../.gitbook/assets/image (15).png>)\

* Total TP percentages should equal 100% of your position.
* Optional: adjust **slippage** and enable **Sell-protection** in settings.

Once active and tokens are bought, Thor automatically places your TP/SL.\
\
⚠️ If you enable it, it will work only for new trades, not for existing ones.

***

### ⚠️ Important Notes

Auto Sell settings apply **per purchase**, not across your total position.\
If you make multiple buys, each will have its own linked auto-sell rules.

Be mindful of:

1. **Stacked Sells:** Multiple active presets may trigger multiple times per purchase.
2. **Multiple Buys:** Each buy tracks its own TP/SL targets — results compound separately.
3. **Best Practice:** After each new buy, clear or update your previous auto-sell presets to avoid double-triggering.

***

**Pro tip:** Use Auto Sell + [Thor’s trailing](trailing-stop-loss.md) to automate exits like a pro while keeping your capital moving.

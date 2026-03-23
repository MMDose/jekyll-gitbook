---
icon: ban
---

# Trailing Stop-Loss

### What is a Trailing Stop-Loss?

A **Trailing Stop-Loss** is an advanced version of a standard stop-loss.

Instead of remaining fixed, the stop price **automatically moves upward as the token price increases**. This allows you to **lock in profits while limiting downside risk**, making it ideal for capturing strong momentum without giving back gains during pullbacks.

***

### Example

You set:

* **Take Profit:** +200%
* **Stop Loss / Drawdown:** -40%

If the token pumps **+190%** and then starts to drop, the outcome depends on whether the trailing stop is enabled.

| Scenario                   | Result                                                                                                                                                   |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Without Trailing Stop-Loss | The position stays open until the price drops to **-40%**, which can turn a profitable trade into a loss.                                                |
| With Trailing Stop-Loss    | The stop price **moves upward with the price**, securing profits. If the price peaks at **+190%**, the stop adjusts to about **+74%**, locking in gains. |

***

### Formula

The trailing stop is calculated using the following formula:

\text{Stop Price} = \text{Highest Price} \times (1 - \text{Drawdown})

Example calculation:

| Highest Price Reached | Drawdown | Stop Price |
| --------------------- | -------- | ---------- |
| +190%                 | 40%      | +74%       |

This means the trade will **automatically close in profit** if the price drops to that level.

***

### How to Enable Trailing Stop-Loss

{% hint style="info" %}
Trailing Stop-Loss Setup Tutorial: [YouTube](https://youtube.com/shorts/Z-GTnAjdH1I)&#x20;
{% endhint %}

| Step | Action                                                                                                                                         |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | <p>Open <strong>Settings</strong><br></p><p><img src="../../.gitbook/assets/image (43) (1).png" alt="" data-size="original"></p>               |
| 2    | <p>Click on <strong>Trading Settings</strong><br></p><p><img src="../../.gitbook/assets/image (44).png" alt="" data-size="original"></p>       |
| 3    | <p>Enable <strong>Auto Sell</strong><br><br><img src="../../.gitbook/assets/image (46) (2).png" alt=""></p>                                    |
| 4    | <p>Activate <strong>Trailing Stop-Loss</strong><br></p><p><img src="../../.gitbook/assets/image (47) (1).png" alt="" data-size="original"></p> |


# Whales Mode

***

#### Whales Mode <a href="#whales-mode" id="whales-mode"></a>

When enabled, Whales Mode restricts chat to verified token holders who meet a minimum holding requirement.

**How verification works:**

1. Admin enables Whales Mode and sets the minimum token holding requirement
2. Users verify by sending 1 token to the Heimdall verification wallet
3. Users can verify multiple wallets
4. Heimdall checks holdings every 30 minutes

**Behavior:**

* Users who fall below the minimum are automatically muted with a notification
* If a previously qualified user sells their tokens, they receive a different message indicating their holdings dropped
* Users are automatically unmuted when holdings are restored
* Notifications have a 24-hour cooldown to prevent spam
* Admins and whitelisted users are always exempt

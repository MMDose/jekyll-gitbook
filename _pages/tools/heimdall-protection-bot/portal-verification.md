# Portal Verification

***

#### Portal Verification <a href="#portal" id="portal"></a>

New users must verify through a web portal before accessing the group. The portal serves two purposes: confirming the user is human, and collecting device fingerprint data for alt account detection.

The portal supports customizable welcome text, an image, and inline buttons. Users who don't verify within the configured time receive reminders.

***

#### Permban Propagation <a href="#permban" id="permban"></a>

When a user is permanently banned, the ban is enforced across **ALL Heimdall-protected groups**. This creates a network-wide defense against persistent bad actors.

{% hint style="info" icon="triangle-exclamation" %}
**Alt Account Detection:** If a permabanned user creates a new Telegram account, Heimdall detects it through fingerprint matching during portal verification and automatically bans the alt account as well.
{% endhint %}

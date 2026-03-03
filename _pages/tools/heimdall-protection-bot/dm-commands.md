# DM commands

***

{% hint style="info" %}
These commands work when messaging the bot directly in private chat.
{% endhint %}

### User Information

#### <mark style="color:blue;">/info</mark> <mark style="color:purple;">(DM)</mark>&#x20;

`/info @username | /info UserID`

Same as group /info but available in DM. You can also forward a message from a user with hidden identity to automatically resolve who they are.

***

#### <mark style="color:blue;">/groupinfo</mark> <mark style="color:purple;">(DM)</mark>&#x20;

`/groupinfo GroupID`

Get information about who installed Heimdall in a specific group.

***

#### <mark style="color:blue;">/getreports</mark> <mark style="color:purple;">(DM)</mark>

`/getreports @username | /getreports UserID`

View all reports for a user (works same as in groups).

***

### Group Configuration via DM

#### <mark style="color:blue;">/filter</mark> <mark style="color:red;">(Admin)</mark> <mark style="color:purple;">(DM)</mark>&#x20;

`/filter word response /filter "phrase" response`

Add filters via DM when configuring a group through the bot. Works same as in-group /filter command.

***

#### <mark style="color:blue;">/removefilter</mark> <mark style="color:red;">(Admin)</mark> <mark style="color:purple;">(DM)</mark>&#x20;

`/removefilter keyword`

Remove a filter via DM when configuring a group.

***

#### <mark style="color:blue;">/removeallfilters</mark> <mark style="color:$danger;">(Admin)</mark> <mark style="color:purple;">(DM)</mark>

`/removeallfilters`

Remove all filters via DM when configuring a group.

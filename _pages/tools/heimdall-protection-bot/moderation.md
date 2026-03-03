# Moderation

***

### Ban & Unban

#### <mark style="color:blue;">/ban</mark> <mark style="color:red;">(Admin)</mark>

`/ban @username | /ban UserID | Reply with /ban`

Ban a user from the group. Can be used by replying to a message, mentioning a user, or providing a UserID.

***

#### <mark style="color:blue;">/unban</mark> <mark style="color:red;">(Admin)</mark>

`/unban @username | /unban UserID`

Unban a previously banned user, allowing them to rejoin the group.

***

#### Mute & Unmute

#### <mark style="color:blue;">/mute</mark> <mark style="color:red;">(Admin)</mark>

`/mute @username [duration] | Reply with /mute`

Mute a user, preventing them from sending messages. Optional duration (e.g., 1h, 1d, 1w). Without duration, mute is permanent until unmuted.

***

#### <mark style="color:blue;">/unmute</mark> <mark style="color:red;">(Admin)</mark>

`/unmute @username | /unmute UserID`

Unmute a user, restoring their ability to send messages. Resets their deleted message counter and removes pending verifications.&#x20;

***

### Message Management

#### <mark style="color:blue;">/delete</mark> <mark style="color:red;">(Admin)</mark>&#x20;

`Reply to a message with /delete`

Delete the replied-to message.

***

#### <mark style="color:blue;">/report</mark> <mark style="color:$success;">(All Users)</mark>&#x20;

`Reply with /report | /report @username [reason]`

Report a user or message to group admins. Creates a report record and notifies admins with ban/mute buttons.

***

#### <mark style="color:blue;">/lock</mark> <mark style="color:red;">(Admin)</mark>

`/lock`

Lock the chat, preventing all non-admin members from sending messages. Shows confirmation buttons.

***

#### <mark style="color:blue;">/unlock</mark> <mark style="color:red;">(Admin)</mark>

`/unlock`

Unlock the chat, allowing all members to send messages again. Shows confirmation buttons.

***

### User Management

#### <mark style="color:blue;">/whitelist</mark> <mark style="color:red;">(Admin)</mark>

`/whitelist @username | /whitelist UserID`

Manually whitelist a user, exempting them from anti-spam checks and automatic moderation. Resets their deleted message counter. Note: Users are also automatically whitelisted after 10 safe messages (see [Automatic Whitelisting](https://trafficbots.xyz/odin/docs/heimdall_documentation.html#auto-whitelisting)).

***

#### <mark style="color:blue;">/exclude</mark> <mark style="color:$success;">(All Users)</mark>

`/exclude | /exclude @username (admin only)`

Exclude yourself (or a specified user if admin) from the /all mention feature.

***

#### <mark style="color:blue;">/removedeletedaccounts</mark> <mark style="color:red;">(Admin)</mark>

`/removedeletedaccounts`

Scan and remove all deleted Telegram accounts from the group.

***

#### <mark style="color:blue;">/info</mark> <mark style="color:$success;">(All Users)</mark>

`/info @username | /info UserID | Reply with /info`

Get detailed information about a user including: permban status, report count, mute count, ban count, whitelist status, verification status, and recent deleted messages.

***

#### <mark style="color:blue;">/getreports</mark> <mark style="color:$success;">(All Users)</mark>&#x20;

`/getreports @username | /getreports UserID`

View all reports filed against a specific user, including both message content and reasons.

***

### Inactive User Management

#### <mark style="color:blue;">/inactive</mark> <mark style="color:red;">(Admin)</mark>

`/inactive [days] | /inactivecount [days]`

Get count of users who haven't sent a message in X days (default: 7 days).

***

#### <mark style="color:blue;">/inactivelist</mark> <mark style="color:red;">(Admin)</mark>&#x20;

`/inactivelist [days]`

List inactive users with their UserID, days since last message, and total message count. Shows first 50 users.

***

#### <mark style="color:blue;">/kickinactive</mark> <mark style="color:red;">(Admin)</mark>&#x20;

`/kickinactive [days]`

Warn inactive users by mentioning them. Users who don't respond within 1 hour will be automatically removed. Skips admins and whitelisted users.







***

# Filters

***

{% hint style="info" %}
**How Filters Work**

Filters create automatic responses when specific keywords or phrases are detected in messages.

**Single-word filters:** Match when used as a command (e.g., typing "ca" or "/ca" triggers the filter)

**Multi-word filters:** Match when the phrase appears ANYWHERE in a message (case-insensitive)
{% endhint %}

***

#### <mark style="color:blue;">/filter</mark> <mark style="color:red;">(Admin)</mark>

`/filter word response text here /filter "multi word phrase" response text here`

Create a new filter. For single words, the word becomes a trigger command. For multi-word phrases, wrap in quotes - it will match anywhere in messages.

**Examples:**

`/filter website https://example.com` - Triggers on /website or website

`/filter "when moon" Soon! Keep holding!` - Triggers whenever "when moon" appears in any message.

***

#### <mark style="color:blue;">/filters</mark> <mark style="color:$success;">(All Users)</mark>

`/filters`

Display all active filter keywords/phrases for the group.

***

#### <mark style="color:blue;">/removefilter</mark> <mark style="color:red;">(Admin)</mark>

`/removefilter keyword`

Remove a specific filter by its keyword.

***

#### <mark style="color:blue;">/removeallfilters</mark> <mark style="color:red;">(Admin)</mark>

`/removeallfilters`

Remove ALL filters from the group. Use with caution!

***

{% hint style="info" icon="check" %}
**Special Filter: CA**

Setting a filter with keyword "ca" or "/ca" will also automatically set the group's contract address, enabling the `/mcap` command and other crypto features.
{% endhint %}

---
description: This page will guide you through different Utility commands available.
---

# Utility

### AFK Commands and Arguments

AFK command is used to show AFK status by adding AFK in nick and a reason (optional) so whenever someone pings you, they know that you are currently AFK

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/afk [reason]</code></td><td>Sets your status as afk with the provided reason (if any)</td><td></td></tr><tr><td><code>/afk ignore &#x3C;#channel></code></td><td>Ignores a channel so bot won't remove your status even if you chat in that channel.</td><td></td></tr><tr><td><code>/afk disable &#x3C;channel></code></td><td>Removes the channel from ignored list.</td><td></td></tr><tr><td><code>/afk clear [@user]</code></td><td>Clears your or the mentioned user's AFK status. </td><td></td></tr><tr><td><code>/afk list</code></td><td>Shows a list of all the users having AFK status</td><td></td></tr></tbody></table>

{% hint style="success" %}
Bot will not be able to add `AFK` in the nicknames of users having a role above the bot.
{% endhint %}

### Polls and Reminder Commands

{% tabs %}
{% tab title="Poll Commands" %}
<table><thead><tr><th>Command Name </th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/poll create &#x3C;question> &#x3C;option 1> &#x3C;option 2></code> <br><code>[option 3].....[option 9]</code> </td><td>Creates a poll with a question and minimum of 2 options (max options : 9)</td><td></td></tr><tr><td><code>/poll end &#x3C;message_id></code>  </td><td>Ends the poll with the given message id.</td><td></td></tr><tr><td><code>/poll show &#x3C;message_id></code></td><td>Returns the result of the given poll</td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Reminder Commands" %}
<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/reminder add &#x3C;duration> [message]</code></td><td>Creates a reminder with the given duration and message (if given any)</td><td></td></tr><tr><td><code>/reminder list</code></td><td>Returns all the reminders in the server</td><td></td></tr><tr><td><code>/reminder cancel &#x3C;message_id></code></td><td>Cancels the reminder with the given ID</td><td></td></tr><tr><td><code>/reminder cancel all</code></td><td>Cancels all the reminders of that server.</td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

### Other Commands and Arguments

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/color &#x3C;color name/hex code></code></td><td>Gives information about the specified color.</td><td></td></tr><tr><td><code>/dashboard</code></td><td>Returns a link to dashboard.</td><td></td></tr><tr><td><code>/help [command_name]</code></td><td>Returns important links, prefix etc or gives info about specific command (if provided)</td><td></td></tr><tr><td><code>/invite</code></td><td>Returns invite link of the bot</td><td></td></tr><tr><td><code>/ping</code></td><td>Returns Api and Bot ping</td><td></td></tr><tr><td><code>/steal &#x3C;emoji | emoji url> [emoji name]</code></td><td>Adds the specified emoji to the server with the given name (if provided any)<br>Name should be at least 2 letters long.</td><td></td></tr><tr><td><code>/variables</code></td><td>Returns a link for the variables page used in invite announcements.</td><td></td></tr><tr><td><code>/vote</code></td><td>Returns the <a href="https://top.gg/bot/718501137484873748/vote">Top.gg </a>link for voting the bot</td><td></td></tr><tr><td><code>/weather &#x3C;place> [degree]</code></td><td>Returns weather of the specified place in fahrenheit or celsius </td><td></td></tr><tr><td><code>/verify</code></td><td>Toggles the verification process<br>(Module should be enabled in order to use this)</td><td></td></tr></tbody></table>

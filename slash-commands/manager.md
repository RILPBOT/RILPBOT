---
description: This page will help you with all the Management Commands
---

# Manager

### List of Basic Management Commands

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/addrole &#x3C;name> [color] [icon] [hoist : True | False]</code></td><td>Creates a role with selected options.<br>Icon option is for server with level 2 boost or above while hoist means if the role should be displayed separately from other roles.</td><td></td></tr><tr><td><code>/deleterole &#x3C;role></code></td><td>Deletes the selected role.</td><td></td></tr><tr><td><code>/listroles &#x3C;limit></code></td><td>Returns a list of all/specified number of roles present in the server.</td><td></td></tr><tr><td><code>/role give &#x3C;user> &#x3C;role></code></td><td>Gives the specified role to mentioned user</td><td></td></tr><tr><td><code>/role remove &#x3C;user> &#x3C;role></code></td><td>Removes the specified role to mentioned user</td><td></td></tr><tr><td><code>/nickname &#x3C;user> &#x3C;nickname></code></td><td>Changes the nickname of the specified user.</td><td></td></tr></tbody></table>

### Dump Command and Arguments

<table data-header-hidden><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/dump &#x3C;role> [filter]</code></td><td>Returns the list of members of mentioned role with specified filter (if any)</td><td></td></tr></tbody></table>

<table><thead><tr><th>Filter Options</th><th>Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>Discriminator</code></td><td>Returns the list of specified role in the order of User's Discriminator</td><td></td></tr><tr><td><code>Username</code></td><td>Returns the list of specified role in the order of Usernames</td><td></td></tr><tr><td><code>ID</code></td><td>Returns the list of specified role in the order of their <a href="https://rilp-bot.gitbook.io/rilp-bot/wEiqC0iTql2tIUve8C8N/getting-started/basics#copying-user-ids">Discord ID</a></td><td></td></tr><tr><td><code>Account Create Date</code></td><td>Returns the list of specified role in the order of User's Account Creation Date</td><td></td></tr><tr><td><code>Server Join Date</code></td><td>Returns the list of specified role in the oder of User's Server Join Date</td><td></td></tr></tbody></table>

### Purge Command and Arguments

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/purge messages &#x3C;count> [channel]</code></td><td>Deletes the messages with the specified count and in specified channel.</td><td></td></tr><tr><td><code>/purge bots &#x3C;count> [channel]</code></td><td>Deletes the messages sent by bot.</td><td></td></tr><tr><td><code>/purge user &#x3C;user> &#x3C;count> [channel]</code></td><td>Deletes the messages sent by the user.</td><td></td></tr><tr><td><code>purge embeds &#x3C;count> [channel]</code></td><td>Deletes the messages containing embeds.</td><td></td></tr><tr><td><code>/purge humans &#x3C;count> [channel]</code></td><td>Deletes the messages sent by humans.</td><td></td></tr><tr><td><code>/purge mentions &#x3C;count> [channel]</code></td><td>Deletes the messages containing mentions (limit 100)</td><td></td></tr><tr><td><code>/purge match &#x3C;content> &#x3C;count> [channel]</code></td><td>Deletes the messages having the provided content.</td><td></td></tr><tr><td><code>/purge startswith &#x3C;content> &#x3C;count> [channel]</code></td><td>Deletes the messages which starts with the provided content</td><td></td></tr><tr><td><code>/purge endswith &#x3C;content> &#x3C;count> [channel]</code></td><td>Deletes the messages which ends with the provided content</td><td></td></tr><tr><td><code>/purge emojis &#x3C;count> [channel]</code></td><td>Deletes the messages containing emojis</td><td></td></tr><tr><td><code>/purge links &#x3C;count> [channel]</code></td><td>Deletes the messages containing links</td><td></td></tr><tr><td><code>/purge attachments &#x3C;count> [channel]</code></td><td>Deletes the messages containing attachments</td><td></td></tr></tbody></table>

{% hint style="info" %}
Messages older than 14days cannot be deleted&#x20;
{% endhint %}

### Custom Command (CC) Commands and Arguments

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/cc add &#x3C;command name> &#x3C;command output> [dm response] [delete after execution]</code></td><td>Adds the custom command with the given command name, output and option to whether dm the user with the output, or delete the command text after using it.</td><td></td></tr><tr><td><code>/cc delete &#x3C;command name></code></td><td>Deletes the custom command with the given name.</td><td></td></tr><tr><td><code>/cc list</code></td><td>Lists all the custom commands with their output and settings in the server.</td><td></td></tr><tr><td><code>/cc edit &#x3C;command name> &#x3C;command output> [dm response] [delete after execution]</code></td><td>Edits the custom command with the given command name, content and other settings.</td><td></td></tr><tr><td><code>/cc toggle &#x3C;command name></code> <br><code>&#x3C;toggle : On | Off></code></td><td>Toggles on or off the custom command with the given name.</td><td></td></tr></tbody></table>

{% hint style="info" %}
Custom Commands can also be edited from [Dashboard](https://rilp-bot.tech).
{% endhint %}

{% hint style="info" %}
The custom command can only be used with the default `r!` prefix at the moment.
{% endhint %}

### Role Manager Commands and Arguments

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/role multiple &#x3C;type> &#x3C;action> &#x3C;role></code></td><td>Gives or removes the role according to the action specified.</td><td></td></tr><tr><td><code>role in &#x3C;action> &#x3C;in role> &#x3C;role></code></td><td>Gives or removes a role from users with a particular role</td><td></td></tr><tr><td><code>/role status</code></td><td>Checks the current process of <code>role in</code> and <code>role multiple</code> command</td><td></td></tr><tr><td><code>role cancel</code></td><td>Cancels the role process</td><td></td></tr></tbody></table>

Arguments for `/role multiple` command

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><code>Type : all | bots | humans</code></td><td>Takes action on bots, humans or everyone according to it.</td><td></td></tr><tr><td><code>Action : give | remove</code></td><td>Gives or removes the role from specified <code>Type</code></td><td></td></tr></tbody></table>

Arguments for `/role in` command

<table data-header-hidden><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><code>Action : give | remove</code></td><td>To select whether to remove or give role to users with selected role</td><td></td></tr><tr><td><code>In_role</code></td><td>The particular role to whose users you want to take actions on</td><td></td></tr><tr><td><code>Role</code></td><td>The role which you want to give or remove from those particular users.</td><td></td></tr></tbody></table>


---
description: >-
  This page will help you understand what permissions does bot need to work
  flawlessly.
---

# Permissions

[Click here](basics.md#giving-permissions) to check how to give permissions to a bot.

<table><thead><tr><th>Permissions</th><th>Features using it</th><th data-hidden></th></tr></thead><tbody><tr><td><code>Add Reactions</code></td><td>Needed to add reactions for <code>giveaways</code> and <code>polls</code></td><td></td></tr><tr><td><code>Ban Members</code></td><td>For <code>ban</code> command and auto moderation</td><td></td></tr><tr><td><code>Embed Links</code></td><td>This is needed for embedding links in different commands like <code>leaderboard invites</code> etc</td><td></td></tr><tr><td><code>Kick Members</code></td><td>For <code>kick</code> command and auto moderation</td><td></td></tr><tr><td><code>Manage Channels</code></td><td>For features like <code>slowmode</code> and <code>lock/unlock</code> channels</td><td></td></tr><tr><td><code>Manage Emojis</code></td><td>For adding emojis via <code>steal</code> command</td><td></td></tr><tr><td><code>Manage Messages</code></td><td>Needed for <code>giveaway</code> and <code>automoderation</code></td><td></td></tr><tr><td><code>Manage Nicknames</code></td><td>For  <code>nickname</code> command, adding AFK in nicks, and for <code>de-hoist</code> in auto-moderation</td><td></td></tr><tr><td><code>Manage Server</code></td><td>For fetching invites from Invites Tab in Server Settings</td><td></td></tr><tr><td><code>Manage Roles</code></td><td>For <code>adding/deleting</code> roles, mod commands and <code>auto role</code></td><td></td></tr><tr><td><code>Manage Webhook</code></td><td>Bot uses webhook for <a href="../website/dashboard/action-logs.md">Action Logs</a></td><td></td></tr><tr><td><code>Moderate Members</code></td><td><p>Need for <code>mute</code> command and</p><p>auto moderation</p></td><td></td></tr><tr><td><code>View Channels</code></td><td>Required for tracking invites</td><td></td></tr></tbody></table>

{% hint style="success" %}
Giving Bot administrator will directly grant it all the perms required in general as well as in a particular channel.
{% endhint %}

{% hint style="danger" %}
If you are setting up permissions manually make sure to provide the bot with all the permissions in all those channels where <mark style="background-color:blue;">everyone</mark> role doesn't have it.\
For example, the bot needs permissions to see all those channels where you want invites to get counted, so you need to give the **RILP BOT**'s role <mark style="color:green;">MANAGE\_CHANNEL</mark> permissions so that they can access the channel's invites.
{% endhint %}

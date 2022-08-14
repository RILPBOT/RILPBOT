---
description: >-
  This page will help you understand what permissions does bot need to work
  flawlessly.
---

# Permissions

[Click here](basics.md#giving-permissions) to check how to give permissions to a bot.

| Permissions        | Features using it                                                                       |   |
| ------------------ | --------------------------------------------------------------------------------------- | - |
| `Add Reactions`    | Needed to add reactions for `giveaways` and `polls`                                     |   |
| `Ban Members`      | For `ban` command and auto moderation                                                   |   |
| `Embed Links`      | This is needed for embedding links in different commands like `leaderboard invites` etc |   |
| `Kick Members`     | For `kick` command and auto moderation                                                  |   |
| `Manage Channels`  | For features like `slowmode` and `lock/unlock` channels                                 |   |
| `Manage Emojis`    | For adding emojis via `steal` command                                                   |   |
| `Manage Messages`  | Needed for `giveaway` and `automoderation`                                              |   |
| `Manage Nicknames` | For  `nickname` command, adding AFK in nicks, and for `de-hoist` in auto-moderation     |   |
| `Manage Server`    | For fetching invites from Invites Tab in Server Settings                                |   |
| `Manage Roles`     | For `adding/deleting` roles, mod commands and `auto role`                               |   |
| `Manage Webhook`   | Bot uses webhook for [Action Logs](../website/dashboard/action-logs.md)                 |   |
| `Moderate Members` | <p>Need for <code>mute</code> command and</p><p>auto moderation</p>                     |   |
| `View Channels`    | Required for tracking invites                                                           |   |

{% hint style="success" %}
Giving Bot administrator will directly grant it all the perms required in general as well as in a particular channel.
{% endhint %}

{% hint style="danger" %}
If you are setting up permissions manually make sure to provide the bot with all the permissions in all those channels where <mark style="background-color:blue;">everyone</mark> role doesn't have it.\
For example, the bot needs permissions to see all those channels where you want invites to get counted, so you need to give the **RILP BOT**'s role <mark style="color:green;">MANAGE\_CHANNEL</mark> permissions so that they can access the channel's invites.
{% endhint %}

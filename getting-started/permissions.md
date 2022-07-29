---
description: >-
  This page will help you understand what permissions does bot need to work
  flawlessly.
---

# Permissions

{% hint style="success" %}
Giving Bot administrator will directly grant it all the perms required in general as well as in a particular channel.\
Though if you still wish to give perms manually you can read the guide ahead....
{% endhint %}

| Permissions        | Features using it                                                                       |   |
| ------------------ | --------------------------------------------------------------------------------------- | - |
| `Add Reactions`    | Needed to add reactions for `giveaways` and `polls`                                     |   |
| `Ban Members`      | For `ban` command                                                                       |   |
| `Embed Links`      | This is needed for embedding links in different commands like `Leaderboard invites` etc |   |
| `Kick Members`     | For `kick` command and auto moderation                                                  |   |
| `Manage Channels`  | For features like `slow` `mode` and `lock/unlock` channels                              |   |
| `Manage Emojis`    | For adding emojis via `steal` command                                                   |   |
| `Manage Messages`  | <p>Needed for <code>giveaways</code> and</p><p> <code>auto moderation</code></p>        |   |
| `Manage Nicknames` | For  `nickname` command, adding AFK in nicks and for `De-hoist` in Auto-moderation      |   |
| `Manage Server`    | For fetching invites from Invites Tab in Server Settings                                |   |
| `Manage Roles`     | For `adding/deleting` roles, mod commands and `auto role`                               |   |
| `Manage Webhook`   | Bot uses webhook for [Action Logs](../website/dashboard/action-logs.md)                 |   |
| `Moderate Members` | <p>Need for <code>mute</code> command and</p><p>auto moderation</p>                     |   |

{% hint style="danger" %}
If you are setting up perms manually make sure to provide the bot perms in all those channels where everyone role doesn't have it.\
Like for example bot needs perms to see all those channels where you want invites to get counted.
{% endhint %}

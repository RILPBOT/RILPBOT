---
description: This page will help you with the Invite Management through slash commands
---

# Invite Management

### General Invite Commands

| Command Name                                     | Command Description                                                                                                                         |   |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- | - |
| `/invitecodes [@user]`                           | Returns the list of invite codes you or the mentioned user have in the server.                                                              |   |
| `/invited [@user]`                               | Returns your or mentioned user's list of invited members                                                                                    |   |
| `/inviteinfo <invite_code>`                      | Returns information about the given invite code                                                                                             |   |
| `/invites [@user]`                               | Returns the total number and different types of invites you or the mentioned user has                                                       |   |
| `/leaderboard [page]`                            | <p>Returns the invite leaderboard of that server.<br>If page number is provided it will only return that particular page number</p>         |   |
| `/leaderboard [user-id \| user-tag \| username]` | <p>Returns the invite leaderboards with <br><code>user-id | user-tag | username</code> instead of the default <code>user-mention</code></p> |   |

{% hint style="info" %}
Both of the /leaderboard options can be used together to find the desired invite list more precisely.
{% endhint %}

### Invite Commands used to Configure Invites

| Command Name                             | Command Description                                                                                       |   |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------- | - |
| `/addinvites <type> <@user> <amount>`    | Adds `regular` or `suspicious` invites for the mentioned user                                             |   |
| `/removeinvites <type> <@user> <amount>` | Removes `regular` or `suspicious` invites from the mentioned user                                         |   |
| `/resetinvites <@user>`                  | Resets the invite count for mentioned user                                                                |   |
| `/resetinvites <left>`                   | Resets the invite count for users who have left the server.                                               |   |
| `/resetinvites <all>`                    | Resets the invite count for everyone in the server.                                                       |   |
|  `/syncinvites <@user \| everyone>`      | It fetches the invites from Invites Tab of the server and then adds it for everyone or the mentioned user |   |

{% hint style="danger" %}
Sync Invites can be a dangerous command and should be used carefully.
{% endhint %}

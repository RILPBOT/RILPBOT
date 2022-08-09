---
description: This page will help you with all the Management Commands
---

# Manager

### List of Basic Management Commands

| Command Name                                             | Command Description                                                                                                                                                                  |   |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | - |
| `/addrole <name> [color] [icon] [hoist : True \| False]` | <p>Creates a role with selected options.<br>Icon option is for server with level 2 boost or above while hoist means if the role should be displayed separately from other roles.</p> |   |
| `/deleterole <role>`                                     | Deletes the selected role.                                                                                                                                                           |   |
| `/listroles <limit>`                                     | Returns a list of all/specified number of roles present in the server.                                                                                                               |   |
| `/role give <user> <role>`                               | Gives the specified role to mentioned user                                                                                                                                           |   |
| `/role remove <user> <role>`                             | Removes the specified role to mentioned user                                                                                                                                         |   |
| `/nickname <user> <nickname>`                            | Changes the nickname of the specified user.                                                                                                                                          |   |

### Dump Command and Arguments

| `/dump <role> [filter]` | Returns the list of members of mentioned role with specified filter (if any) |   |
| ----------------------- | ---------------------------------------------------------------------------- | - |

| Filter Options        | Description                                                                                                                                                              |   |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | - |
| `Discriminator`       | Returns the list of specified role in the order of User's Discriminator                                                                                                  |   |
| `Username`            | Returns the list of specified role in the order of Usernames                                                                                                             |   |
| `ID`                  | Returns the list of specified role in the order of their [Discord ID](https://rilp-bot.gitbook.io/rilp-bot/wEiqC0iTql2tIUve8C8N/getting-started/basics#copying-user-ids) |   |
| `Account Create Date` | Returns the list of specified role in the order of User's Account Creation Date                                                                                          |   |
| `Server Join Date`    | Returns the list of specified role in the oder of User's Server Join Date                                                                                                |   |

### Purge Command and Arguments

| Command Name                                    | Command Description                                                     |   |
| ----------------------------------------------- | ----------------------------------------------------------------------- | - |
| `/purge messages <count> [channel]`             | Deletes the messages with the specified count and in specified channel. |   |
| `/purge bots <count> [channel]`                 | Deletes the messages sent by bot.                                       |   |
| `/purge user <user> <count> [channel]`          | Deletes the messages sent by the user.                                  |   |
| `purge embeds <count> [channel]`                | Deletes the messages containing embeds.                                 |   |
| `/purge humans <count> [channel]`               | Deletes the messages sent by humans.                                    |   |
| `/purge mentions <count> [channel]`             | Deletes the messages containing mentions (limit 100)                    |   |
| `/purge match <content> <count> [channel]`      | Deletes the messages having the provided content.                       |   |
| `/purge startswith <content> <count> [channel]` | Deletes the messages which starts with the provided content             |   |
| `/purge endswith <content> <count> [channel]`   | Deletes the messages which ends with the provided content               |   |
| `/purge emojis <count> [channel]`               | Deletes the messages containing emojis                                  |   |
| `/purge links <count> [channel]`                | Deletes the messages containing links                                   |   |
| `/purge attachments <count> [channel]`          | Deletes the messages containing attachments                             |   |

{% hint style="info" %}
Messages older than 14days cannot be deleted&#x20;
{% endhint %}

### Custom Command (CC) Commands and Arguments

| Command Name                                                                                 | Command Description                                                                                                                                       |   |
| -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
| `/cc add <command name> <command output> [dm response] [delete after execution]`             | Adds the custom command with the given command name, output and option to whether dm the user with the output, or delete the command text after using it. |   |
| `/cc delete <command name>`                                                                  | Deletes the custom command with the given name.                                                                                                           |   |
| `/cc list`                                                                                   | Lists all the custom commands with their output and settings in the server.                                                                               |   |
| `/cc edit <command name> <command output> [dm response] [delete after execution]`            | Edits the custom command with the given command name, content and other settings.                                                                         |   |
| <p><code>/cc toggle &#x3C;command name></code> <br><code>&#x3C;toggle : On | Off></code></p> | Toggles on or off the custom command with the given name.                                                                                                 |   |

{% hint style="info" %}
Custom Commands can also be edited from [Dashboard](https://rilp-bot.tech).
{% endhint %}

{% hint style="info" %}
The custom command can only be used with the default `r!` prefix at the moment.
{% endhint %}

### Role Manager Commands and Arguments

| Command Name                            | Command Description                                                 |   |
| --------------------------------------- | ------------------------------------------------------------------- | - |
| `/role multiple <type> <action> <role>` | Gives or removes the role according to the action specified.        |   |
| `role in <action> <in role> <role>`     | Gives or removes a role from users with a particular role           |   |
| `/role status`                          | Checks the current process of `role in` and `role multiple` command |   |
| `role cancel`                           | Cancels the role process                                            |   |

Arguments for `/role multiple` command

| `Type : all \| bots \| humans` | Takes action on bots, humans or everyone according to it. |   |
| ------------------------------ | --------------------------------------------------------- | - |
| `Action : give \| remove`      | Gives or removes the role from specified `Type`           |   |

Arguments for `/role in` command

| `Action : give \| remove` | To select whether to remove or give role to users with selected role   |   |
| ------------------------- | ---------------------------------------------------------------------- | - |
| `In_role`                 | The particular role to whose users you want to take actions on         |   |
| `Role`                    | The role which you want to give or remove from those particular users. |   |


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


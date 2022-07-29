---
description: This page will guide you through different Utility commands available.
---

# Utility

### AFK Commands and Arguments

AFK command is used to show AFK status by adding AFK in nick and a reason (optional) so whenever someone pings you, they know that you are currently AFK

| Command Name             | Command Description                                                                 |   |
| ------------------------ | ----------------------------------------------------------------------------------- | - |
| `/afk [reason]`          | Sets your status as afk with the provided reason (if any)                           |   |
| `/afk ignore <#channel>` | Ignores a channel so bot won't remove your status even if you chat in that channel. |   |
| `/afk disable <channel>` | Removes the channel from ignored list.                                              |   |
| `/afk clear [@user]`     | Clears your or the mentioned user's AFK status.                                     |   |
| `/afk list`              | Shows a list of all the users having AFK status                                     |   |

{% hint style="success" %}
Bot will not be able to add `AFK` in the nicknames of users having a role above the bot.\
\
`/afk clear` and `/afk list` are mod only commands meaning only users with mod role, server manager or administrator perms will be able to use the command
{% endhint %}

### Polls and Reminder Commands

{% tabs %}
{% tab title="Poll Commands" %}
| Command Name                                                                                                                 | Command Description                                                       |   |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | - |
| <p><code>/poll create &#x3C;question> &#x3C;option 1> &#x3C;option 2></code> <br><code>[option 3].....[option 9]</code> </p> | Creates a poll with a question and minimum of 2 options (max options : 9) |   |
| `/poll end <message_id>`                                                                                                     | Ends the poll with the given message id.                                  |   |
| `/poll show <message_id>`                                                                                                    | Returns the result of the given poll                                      |   |
{% endtab %}

{% tab title="Reminder Commands" %}
| Command Name                         | Command Description                                                   |   |
| ------------------------------------ | --------------------------------------------------------------------- | - |
| `/reminder add <duration> [message]` | Creates a reminder with the given duration and message (if given any) |   |
| `/reminder list`                     | Returns all the reminders in the server                               |   |
| `/reminder cancel <message_id>`      | Cancels the reminder with the given ID                                |   |
| `/reminder cancel all`               | Cancels all the reminders of that server.                             |   |
{% endtab %}
{% endtabs %}

### Other Commands and Arguments

| Command Name                               | Command Description                                                                                                            |   |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | - |
| `/color <color name/hex code>`             | Gives information about the specified color.                                                                                   |   |
| `/dashboard`                               | Returns a link to dashboard.                                                                                                   |   |
| `/help [command_name]`                     | Returns important links, prefix etc or gives info about specific command (if provided)                                         |   |
| `/invite`                                  | Returns invite link of the bot                                                                                                 |   |
| `/ping`                                    | Returns Api and Bot ping                                                                                                       |   |
| `/steal <emoji \| emoji url> [emoji name]` | <p>Adds the specified emoji to the server with the given name (if provided any)<br>Name should be at least 2 letters long.</p> |   |
| `/variables`                               | Returns a link for the variables page used in invite announcements.                                                            |   |
| `/vote`                                    | Returns the [Top.gg ](https://top.gg/bot/718501137484873748/vote)link for voting the bot                                       |   |
| `/weather <place> [degree]`                | Returns weather of the specified place in fahrenheit or celsius                                                                |   |
| `/verify`                                  | Toggles the verification module                                                                                                |   |

---
description: This page shall guide you through server moderation commands.
---

# Moderation

### Basic Moderation Commands and Arguments

| Command Name                              | Command Description                                                                              |   |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------ | - |
| `/listmods`                               | Returns a list of server moderator roles.                                                        |   |
| `/deafen <user>`                          | Deafens the mentioned user in a voice chat                                                       |   |
| `/forceverify all`                        | Force verifies all the users with pending verification in the server                             |   |
| `/forceverify user <user>`                | Force verifies the mentioned user.                                                               |   |
| `/infractions clear <user \ case_id>`     | Clears all infractions for the user or infractions with the given `case_id`                      |   |
| `/infractions view <user>`                | Returns the list of infractions the user has in the server.                                      |   |
| `/kick <user>`                            | Kicks the mentioned user from the server                                                         |   |
| `/lock [channel] [time] [reason]`         | Locks the channel with given time and reason (if provided)                                       |   |
| `/lockdown start [reason]`                | Starts locking all the channels in the server.                                                   |   |
| `/lockdown exclude <channel or category>` | Excludes the channel/category when `lockdown start` is used                                      |   |
| `/lockdown end [reason]`                  | Ends the lockdown and unlocks all the locked channels.                                           |   |
| `/mute <user> [reason] [time]`            | Timeouts the mentioned user for given time and reason (if provided any)                          |   |
| `/slowmode set [channel] [delay]`         | Sets the slowmode with the given time (default is 6 hours)                                       |   |
| `/slowmode off [channel]`                 | Removes the slowmode for a channel                                                               |   |
| `/softban <user> [reason]`                | Bans the mentioned user to delete all the messages of that user and then quickly unbans him/her. |   |
| `/totalbans`                              | Returns the total number of bans the server has.                                                 |   |
| `/unban <user id> [reason]`               | Unbans the user with the given reason                                                            |   |
| `/undeafen <user>`                        | Un-deafens the user from voice chats.                                                            |   |
| `/unlock [channel]`                       | Unlocks the locked channel.                                                                      |   |
| `/warn <user> [reason]`                   | Warns the user with given reason (if given any)                                                  |   |
| `/warnings view <user>`                   | Returns all the warnings user has received in that server/                                       |   |
| `/warnings clear <user \ case id>`        | Clears all the warnings for a user or clear warning with the given case id.                      |   |

{% hint style="info" %}
You can set the Mod Role from the [Dashboard](https://rilp-bot.tech).
{% endhint %}

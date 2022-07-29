---
description: This page will help you with all the giveaway slash commands
---

# Giveaways

### Giveaway Commands and Arguments

| Command Name                                                       | Command Usage                                                                                                                      |   |
| ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- | - |
| `/giveaway create <prize> <duration> <winners> <#channel> [image]` | <p>Creates a giveaway with given arguments.<br>The image argument embeds the image provided in the giveaway</p>                    |   |
| `/giveaway delete <message_id>`                                    | Deletes the giveaway with the provided message id. Deleting giveaway does not draw any winners                                     |   |
| `/giveaway end <message_id>`                                       | Ends the giveaway with provided message id. Ending giveaway will draw the amount of winners given while creating.                  |   |
| `/giveaway list`                                                   | Returns a list of all the running giveaways in the server.                                                                         |   |
| `/giveaway reroll <message_id> [winner_amount]`                    | <p>Rerolls the giveaway with given message id.<br>If no winner amount is given then it will draw winners given while creating.</p> |   |

{% hint style="info" %}
There are more configurable settings like Giveaway Manager Roles available on [Dashboard](https://rilp-bot.tech).
{% endhint %}

{% hint style="warning" %}
You can have 15 active giveaways in Free version while up to 50 in premium\
\
You can have 25 winners in Free version while up to 100 in premium\
\
Giveaways can last for 4 months in premium version while only 14 days in Free version
{% endhint %}

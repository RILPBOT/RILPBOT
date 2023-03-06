---
description: This page will help you with the Invite Management through slash commands
---

# Invite Management

### General Invite Commands

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/invitecodes [@user]</code></td><td>Returns the list of invite codes you or the mentioned user have in the server.</td><td></td></tr><tr><td><code>/invited [@user]</code></td><td>Returns your or mentioned user's list of invited members</td><td></td></tr><tr><td><code>/inviteinfo &#x3C;invite_code></code></td><td>Returns information about the given invite code</td><td></td></tr><tr><td><code>/invites [@user]</code></td><td>Returns the total number and different types of invites you or the mentioned user has</td><td></td></tr><tr><td><code>/leaderboard [page]</code></td><td>Returns the invite leaderboard of that server.<br>If page number is provided it will only return that particular page number</td><td></td></tr><tr><td><code>/leaderboard [user-id | user-tag | username]</code></td><td>Returns the invite leaderboards with <br><code>user-id | user-tag | username</code> instead of the default <code>user-mention</code></td><td></td></tr></tbody></table>

{% hint style="info" %}
Both of the /leaderboard options can be used together to find the desired invite list more precisely.
{% endhint %}

### Invite Commands used to Configure Invites

<table><thead><tr><th>Command Name</th><th>Command Description</th><th data-hidden></th></tr></thead><tbody><tr><td><code>/addinvites &#x3C;type> &#x3C;@user> &#x3C;amount></code></td><td>Adds <code>regular</code> or <code>suspicious</code> invites for the mentioned user</td><td></td></tr><tr><td><code>/removeinvites &#x3C;type> &#x3C;@user> &#x3C;amount></code></td><td>Removes <code>regular</code> or <code>suspicious</code> invites from the mentioned user</td><td></td></tr><tr><td><code>/resetinvites &#x3C;@user></code></td><td>Resets the invite count for mentioned user </td><td></td></tr><tr><td><code>/resetinvites &#x3C;left></code></td><td>Resets the invite count for users who have left the server.</td><td></td></tr><tr><td><code>/resetinvites &#x3C;all></code></td><td>Resets the invite count for everyone in the server.</td><td></td></tr><tr><td> <code>/syncinvites &#x3C;@user | everyone></code></td><td>It fetches the invites from Invites Tab of the server and then adds it for everyone or the mentioned user</td><td></td></tr></tbody></table>

{% hint style="danger" %}
Sync Invites can be a dangerous command and should be used carefully.
{% endhint %}

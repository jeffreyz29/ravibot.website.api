---
description: Configuration for Ticketing
---

# Ticketing

**Ticketing | 15 commands**

| Command                      | Description                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| `enable-tickets`             | enables ticket system                                                                                                |
| `disable-tickets`            | disables ticket system                                                                                               |
| `set-staff-role`             | sets a staff role that can manage tickets                                                                            |
| `remove-staff-role`          | removes a staff role that can manage tickets                                                                         |
| `set-ticket-category`        | <p>sets tickets to any categories you want</p><p>tickets can also be created without having to be in a category </p> |
| `remove-ticket-category`     | removes tickets from being set to a category                                                                         |
| `setup-ticket`               | sets up a ticket panel                                                                                               |
| `ticket-panel`               | <p>Displays a staff ticket panel </p><p>REQUIRES: <code>staff role</code></p>                                        |
| `new [reason \| optional]`   | creates a new ticket with or without a reason                                                                        |
| `close [reason \| optional]` | closed (deletes) the ticket with or without a reason                                                                 |
| `rename [name]`              | renames a ticket \[you must be in the ticket to rename it]                                                           |
| `set-ticket-msg`             | Sets a custom ticket message to the tickets when created                                                             |
| `setticketlog [#channel]`    | when someone executes the close ticket command it will send the ticket transcript to the channel it has been set to  |
| `add user`                   | adds a user to a ticket                                                                                              |
| `remove user`                | removes a user from a ticket                                                                                         |

**When someone creates a new ticket everyone can see and send a message how can I disable that to only the person who triggers it to read and send messages in the ticket channel?**\
****\
**step 1:**\
`new [reason | optional]` when you trigger this command it creates a new category with the name “Opened Tickets” Do not change the category name for it.\
**Step 2:** \
To disable everyone from reading messages and sending msg in the ticket channel please click [here](https://cdn.discordapp.com/attachments/756287218846531654/778323907459022888/image0.png) to see how to fix the problem. \
**Step 3:** \
run `new [reason | optional]` again.&#x20;

{% hint style="info" %}
Discord will automatically sync its category permissions when new channels are created, with the channels if discord does not sync its perms you must go to the channel settings press "sync perms" to sync them manually.
{% endhint %}

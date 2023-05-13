---
description: Configuration for Ticketing
---

# Ticketing

**Ticketing | 17 commands**

| Command                        | Description                                                                                                         |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| `!enable-tickets`              | enables ticket system                                                                                               |
| `!disable-tickets`             | disables ticket system                                                                                              |
| `!set-staff-role`              | sets a staff role that can manage tickets                                                                           |
| `!remove-staff-role`           | removes a staff role that can manage tickets                                                                        |
| `!set-ticket-category`         | <p>sets tickets to any categories you want</p><p>tickets can also be created without having to be in a category</p> |
| `!remove-ticket-category`      | removes tickets from being set to a category                                                                        |
| `!setup-ticket`                | sets up a ticket panel                                                                                              |
| `!ticket-panel`                | <p>Displays a staff ticket panel</p><p>REQUIRES: <code>staff role</code></p>                                        |
| `!new [reason \| optional]`    | creates a new ticket with or without a reason                                                                       |
| `!close [reason \| optional]`  | closed (deletes) the ticket with or without a reason                                                                |
| `!rename [name]`               | renames a ticket \[you must be in the ticket to rename it]                                                          |
| `!set-ticket-msg [message]`    | Sets a custom ticket message to the tickets when created                                                            |
| `!setticketlog <#channel>`     | when someone executes the close ticket command it will send the ticket transcript to the channel it has been set to |
| `!add user`                    | adds a user to a ticket                                                                                             |
| `!remove user`                 | removes a user from a ticket                                                                                        |
| `!ticket blacklist add/remove` | this adds/removes a user from blacklist when massing with a portal                                                  |

Discord will automatically sync its category permissions when new channels are created, with the channels if discord does not sync its perms you must go to the channel settings press "sync perms" to sync them manually.

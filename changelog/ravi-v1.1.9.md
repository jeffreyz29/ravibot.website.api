---
description: bots official updates will be posted here
---

# Ravi (V1.1.9)

## Friday, March 18, 2022 (EST)

﻿**ANNOUNCEMENT**﻿

﻿﻿Ravi is currently the beta version of `v1.2.0`﻿ Going forward, this will be the only version I will maintain and will work on until it's released.﻿\
\
The following things:\
\- The "\`embed builder﻿" subcommand will not be updated. For now, this version of the embed builder will be kept under beta phase.\
\- The "﻿inviteinfo﻿" subcommand does not retrieve other servers invite information.\
\- Ravi may respond a little faster, you might experience some slow replies, due to the hosting server being wonky some of the time.\
\
﻿If you experience any issues with the new update, please let me know!﻿\
\
Guides & Links:﻿\
Privacy Policy: [https://ravi-docs.gitbook.io/ravi-documentation/privacy-policy﻿](https://ravi-docs.gitbook.io/ravi-documentation/privacy-policy)\
GitHub: [﻿https://github.com/Jeffreyz1129/ravibot.website.api﻿](https://github.com/Jeffreyz1129/ravibot.website.api)\
FAQ: ﻿[https://ravi-docs.gitbook.io/ravi-documentation/faq﻿](https://ravi-docs.gitbook.io/ravi-documentation/faq)\
Guide: ﻿[https://ravi-docs.gitbook.io/ravi-documentation/guide﻿](https://ravi-docs.gitbook.io/ravi-documentation/guide)\
Changelog: ﻿[https://ravi-docs.gitbook.io/ravi-documentation/changelog/ravi-v1.1.9﻿](https://ravi-docs.gitbook.io/ravi-documentation/changelog/ravi-v1.1.9)\
\
﻿If you have any concerns, questions, or suggestions about Ravi, please ask in the support server

## Tuesday, February 15, 2022 (EST)

**Changelog (v1.1.9)**\
**Added**:\
\- `serverlist` - retrieves server invites and displays information on how many servers the bot has connected to

## Sunday, February 13, 2022 (EST)

**Changelog (v1.1.9)**

**Fixed**: \
\- `pinmsg` & `unpinmsg`

Notes: both cmd has been fixed and works functionally now

## Tuesday, February 08, 2022 (EST)

**Changelog (v1.1.9)**

**Updated**: \
Ravi will now automatically leave the guild if the bot doesn't reach minimum server **member requirements** (human members). you will need to have 65 real human members :)

## Tuesday, February 01, 2022 (EST)

**Changelog (v1.1.9)**\
****\
**Updated:**\
**-** commands layout have been changed for easier reading

## Sunday, January 30, 2022 (EST)

**Changelog (v1.1.8)**

**Added**:

* `!calc` - calculates a given expression

**Others**:

* none

## Thursday, January 20, 2022 (EST)

**Changelog (v1.1.8)**

**Added**:

* `!serverinfo` - displays information about the provided server

**Others**:

* none

## Saturday, January 15, 2022 (EST)

**Changelog (v1.1.8)**

**Added**:

1. `add user` - adds a user to a ticket
2. `remove user` - removes a user from a ticket

**example usage**: using user mentions/user ids

* `!add user @somebody` | `!add user 1234567890`
* `!remove user @somebody` | `!remove user 1234567890`

**Others**:

* none

## Friday, January 14, 2022 (EST)

**Changelog (v1.1.8)**

Bug Fix:

* `add pm/am`
* `remove pm/am`

notes: the cmd now should be working properly and smoothly without having errors!

Others:

* none

## Wednesday, January 12, 2022 ( EST )

**Changelog (v1.1.8)**

Added:

* `pinmsg/unpinmsg`

Notes: pins a message from a given message ID/ unpins a message from a given message ID

example usage:

* `!pinmsg 12345678` | `!unpinmsg 12345678`

Others:

* none

## Sunday, January 2, 2022 ( EST )

**Changelog (v1.1.8)**

Added:

* `timeout` - sets the timeout to a certain user **eg**: `!timeout <user/userid> <unix>`

**usage**: `!timeout @somebody 1w`

**Notes**:

* timeouts can not be set for more than 1 week due to discord limits

that's all for today best,

your developer Jeffrey

## Sunday, December 12, 2021 ( EST )

**Changelog (v1.1.8)**

Added:

* `invid` - retrieves a certain guild's ID server invite notes: the bot must be mutual in order for this to work

Others:

* booting up bot now is able to reply to your commands 5x faster than before
* adding partnership count features soon
* updated the bot website a bit
* going to update `suggestions` modules with features of able to: `accept, deny cmds, etc`
* going to add `hapm` the module commands just like when you use `!add pm/am` % `!remove pm/am` on the next update

That's all for today best,

your developer Jeffrey

## **Tuesday, November 30, 2021 (EST)**

* added [privacy policy](../privacy-policy.md) (these bot rules and terms of services will and can be changed at any time)
* The Bot is also verified :smile:

## Wednesday, November 17, 2021 (EST)

**Changelog (v1.1.8)**

**After some problems we had when deploying it, finally, it's live.**

Added:

* New ticket system !! use `!nani tickets` for more information
* New welcome/leave system check [here](https://ravi-docs.gitbook.io/ravi-documentation/commands-list/welcome-system) for more info on how to set this up
* ticket reaction panels !! ( we still can use the old version of just running the (`!new`) creation ticket cmd but now both are optional use!

Removed:

* `nafk` - your AFK can now be auto-disabled when you type smth back on any channels, etc (this command has been depreciated, If you can't remove your AFK just "set a new one" and then type in any channels to get them disabled)

Changed:

* Changed paginator to use the button instead of reaction.
* Changed the bot response for "help panel" (`!help`)
* Moved detailed examples from help commands to docs page as it's more difficult to maintain for changes.

Website:

* ravi's website changelog will be updated tonight

**Hop over to our support server If you need help with the new changelogs of Ravi's command changes.**

## Saturday, June 5, 2021 (EST)

**Change log (V.1.6)**

* Gonna be doing a series of updates over the next week or two. I'm currently going over each command to optimize code and improve functionality and I'll update here if there are any command execution changes.
* This is just a heads up that `inviteinfo` the module will be changed in terms of implementation to allow servers to have a history of their invite codes (this includes expired invites).

Embed Updates:

* Currently, the embed creation commands are yet to still be in (beta)

Partnerships Update:

* I am planning to implement a partnership counting system into the bot. (this is gonna take some time)

Notes:

The update is currently being applied gradually per-shard. So, be patient if the update hasn't reached your server yet.

Guides: [here](https://ravi-docs.gitbook.io/ravi-documentaion/guide)

On a final note, If you have any questions or are just curious, feel free to join the support server and ask !!

## Tuesday, February 2, 2021 ( EST )

**Changelog (v1.1.3)**

Fixed:\
\- embedded all error/ & successful Messages

Added:\
\- `!guide` : a guide to the bot

Others:\
\- Finally, I wanted to remind you all that command cooldowns are not here just to annoy you, but to ensure that Ravi does not get rate limited (slow). I did my best to make them as non-disruptive as possible, I will not lower cooldowns even if you ask. but I will try something new if that doesn’t work.

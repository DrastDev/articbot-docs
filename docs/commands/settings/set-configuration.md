# Adjusting the Configuration
ArticBot is pre-initialized with a basic per-server configuration, which should fit the needs of most most server owners, however, we all want to customize this at some point, so here are all the available customization options. 

!!! warning
    There are several methods in place to ensure that incorrect values don't get entered, however, we can't guarantee you won't break the bot in your server by setting incorrect values. If you do, have no fear, the team at our support server will be glad to help you out.

## Prefix
This specifies the prefix used used to run commands on the bot with. The default prefix is `$` and an example command is `$help`.

To change the prefix, use `$setconf prefix [prefix]`

## Moderator Log Channel
This channel is where events like a user leaving, getting kicked or banned are recorded. It would be similar to the audit function, but with not quite as many details.

To set the moderator log channel, use `$setconf modLogChannel [channel]`

## Built-In Debugger
The built-in debugger auto-logs any commands run in your server, to allow you to better pinpoint where an error might have occured in the bot, and what could have caused it.

To enable/disable the debugger, use `$setconf debuggerEnabled [true|false]`
To set the debugger channel, use `$setconf debuggerChannel [channel]`

## Chat Bot
For details on the chatbot, click [here](/commands/fun/chatbot)

## Swear Filter
The swear filter on ArticBot is used to filter profane language in a server, and automatically warn the user.

To enable/disable the swear filter, use `$setconf swearFilter [true|false]`

## User Welcomer
When user's join, Discord has a built-in welcoming function, but sometimes it's nice to have your own custom message. ArticBot provides this functionality, with a twist.

To enable the welcomer, use `$setconf welcomerEnabled [true|false]`
To set the welcomer channel, use `$setconf welcomerChannel [channel]`
To change the default welcome message, use `$setconf welcomerMessage [message]`

!!! info
    When setting a custom welcome message, use `{{user}}` to specify where you want the name of the user to be put. For example, `Welcome {{user}}, thank you for joining our server!`

## Auto Role
In a server where you like everyone to have roles, you can use the autorole function to automatically assign roles to user's as they join.

To enable/disable autorole, use `$setconf autoRole [true|false]`
To change the default role to be assigned, use `$setconf autoRoleName [role-name]`

## Announcements Channel
The announcement function in ArticBot requires a channel that announcements will be sent to.

To set the channel, use `$setconf announcementsChannel [channel]`.

## Team Announcements Channel

!!! warning
    This is only applicable to premium users of ArticBot

The team announcement function in ArticBot is for team announcements, and requires a channel for the announcements to be sent to.

To set the channel, use `$setconf teamAnnouncementsChannel [channel]`

## Purge Completion
When purging messages, you can optionally have a notification shown to let you know how many messages were purged.

To enable/disable this message, use `$setconf showPurgeCompletion [true|false]`

## Say Command
ArticBot has a Say command, that allows user's to make the bot say things. By default, this command is only enabled for Administrator's and Moderator's, but can be allowed for regular users.

To enable/disable the say command for all user's, use `$setconf restrictSayCommand [true|false]`

## Invite Link Deleter
You can automatically delete invite link's sent by user's with ArticBot, to prevent user's from promoting their server in your's.

!!! warning
    This only restrict's direct Discord Invite Link's, and will not filter link's that redirect to a Discord Invite Link

To enable/disable the invite link deleter, use `$setconf removeInviteLinks [true|false]`

## Beta Commands
To enable beta commands on your server, you must join our support server and submit a request. You can do so by clicking [here](https://discord.gg/ZBYN5uB)

## Custom Audit Logger 
The custom audit logger in ArticBot can be used to log more than just the kicks, warns and bans. It can be used to log when messages are deleted, or edited. 

!!! warning
    This is still a work in progress, and is not completely accurate. Some of the message's sent in the audit logger may not be accurate.

To enable/disable the audit logger, use `$setconf customAuditLogger [true|false]`
To set the audit logger channel, use `$setconf customAuditLoggerChannel [channel]`

## Custom Rules
ArticBot comes with a set of predefined rule's that should suit most owner's needs, however, depending on the audience your server is geared towards, you may want to customize the rules.

To change the default rules channel, use `$setconf rulesChannel [channel]`
To set custom rules, use `$setconf customRules [rules]`

!!! warning
    These command's may not be implemented for your server yet.

## Subscriptions
ArticBot premium has a subscriptions feature that allows user's to subscribe to announcements, then send's them a direct message when announcements are posted. 

To change the subscription role, use `$setconf subscriptionRole [role]`

!!! warning
    You will be able to set a subscription role without ArticBot premium, however, this will have no effect on subscription options until premium is enabled.
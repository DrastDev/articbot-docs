# Getting Started

To join our support server, click [here](https://discord.gg/ZBYN5uB)

## Introduction

Throughout this documentation, there will be a steady syntax for all commands. Any arguments wrapped in `[]` are required arguments. Any arguments wrapped in `()` are optional arguments. If you are experiencing an issue with the syntax, feel free to join our support server using the link above, and we will be glad to assist.

## Commands

Commands are separated into three different categories:

- Free
- Premium
- Beta

To gain access to beta commands, you must join the support server and ask for permission there.

To gain access to premium commands, you must donate at least $5 to ArticBot, then you will automatically be given access. Please note, that is done for your user only, this will not apply to your guilds. To get premium commands for your whole guild, you must pay $30.

The following commands will be enabled by default:

- Fun:
    - [8ball](commands/fun/8ball/)
    - [LMGTFY](commands/fun/lmgtfy/)
    - [Say](commands/fun/say/)
- Utility:
    - [Guild Stats](commands/utility/guildstats/)
    - [Ping](commands/utility/ping/)
    - [Test](commands/utility/test/)
    - [Version](commands/utility/version/)
    - [Whois](commands/utility/whois/)
- Moderation:
    - [Ban](commands/moderation/ban/)
    - [Kick](commands/moderation/kick/)
    - [Purge](commands/moderation/purge/)
    - [Warn](commands/moderation/warn/)
- Gamification:
    - [Leaderboard](commands/gamification/leaderboard/)
    - [Points](commands/gamification/points/)
    - [Set Points](commands/gamification/setpoints/)
    - [Cleanup](commands/gamification/cleanup/)
- Rules:
    - [Show Rules](commands/rules/show-rules/)
    - [Send Rules](commands/rules/send-rules/)
- Settings:
    - [Set Configuration](commands/settings/set-configuration/)
    - [Show Configuration](commands/settings/show-configuration/)
    - [Show Configuration Details](commands/settings/show-configuration-details/)
    - [Clear Configuration](commands/settings/clear-configuration/)
- Help:
    - [Commands](commands/helpcommands)
    - [Help](commands/help/help)
    - [Premium Commands](commands/help/premium-commands)

The following premium commands will automatically be available after you purchase a subscription:

- [Ignore / Unignore](commands/premium/ignore-unignore/)
- [Lockdown](commands/premium/lockdown/)
- [Per-Server Blacklist](commands/premium/per-server-blacklist/)
- [Subscriptions](commands/premium/subscriptions/)
- [Team Announcements](commands/premium/team-announcements/)

The following beta commands will automatically be available once we have approved your request for beta commands:

- [Change](commands/beta/change)

## Initial Configuration

ArticBot is initialized with a standard server configuration, which is shown below.

```json
  prefix: "$",
  modLogChannel: "mod-log",
  welcomerEnabled: "true",
  welcomeChannel: "welcome",
  welcomeMessage:
    "Say hello to {{user}}, everyone! Thanks for joining the server!",
  debuggerEnabled: "false",
  debuggerChannel: "debug",
  autoRole: "false",
  autoRoleName: "Member",
  announcementsChannel: "announcements",
  teamAnnouncementsChannel: "team-announcements",
  showPurgeCompletion: "true",
  restrictSayCommand: "false",
  removeInviteLinks: "false",
  enableBetaCommands: "false",
  customAuditLogger: "false",
  customAuditLoggerChannel: "audit-log",
  swearFilter: "true",
  customRules: "",
  rulesChannel: "rules",
  chatBotEnabled: "false",
  chatBotChannel: "chatbot"
```

For more details on per-server configuration, see the article [here](commands/settings/set-configuration/)

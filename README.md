# BetterSlowmode
Original repository: [link](https://github.com/aeramos/BetterSlowmode)

## Additions
- Custom reply with a removal reason
- Docker compose for easy setup
- Cleaning up the repo

## Overview
BetterSlowmode is a verified Discord bot designed to give users more power when defining slowmodes for text channels.
With the bot, users can specify which types of content will be blocked during the slowmode: text or images or both.

BetterSlowmode is designed for as much customization as possible. Your slowmodes can be as short as 1 second, or as long
as a year. You can even specially include or exclude certain members or roles to/from the slowmode!

## How to use
It's very simple! Try out the commands below to get started. Always remember that you can use `@BetterSlowmode help` 
for a list of all the commands, and `@BetterSlowmode help [command]` to get help for a specific command.
```
@BetterSlowmode
@BetterSlowmode help
@BetterSlowmode help set
@BetterSlowmode set 1h 30m 10s -exclude @aeramos
@BetterSlowmode set-image 1d -include @aeramos
@BetterSlowmode set-text 1y
@BetterSlowmode status
@BetterSlowmode remove
@BetterSlowmode reset @aeramos
@BetterSlowmode info
```

BetterSlowmode also supports slash commands! If enabled, slash commands can be used by pressing `/` then selecting or
typing any BetterSlowmode command, like `/set` or `/status`. 

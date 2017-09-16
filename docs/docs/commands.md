All commands are catagorized by groups. Each of the following sections is a group.

The syntax of the command usage is:

`Optional paramater: []`

`Required paramater: <>`

##Table Of Contents
- [Administration](#administration)
- [Botowners](#botowners)
- [Crime](#crime)
- [Gambling](#gambling)
- [General](#general)
- [Moderation](#moderation)
- [Owners](#owners)
- [Sponsor](#sponsor)
- [System](#system)

### Administration

These commands may only be used by a user with the set mod role with a permission level of 2 or the Administrator permission.

Command | Description | Usage
---------------- | --------------| -------
Disablewelcome|Turns off the welcome message.|`+disablewelcome`
Setmodlog|Sets the mod log channel.|`+setmodlog <#channel>`
Setmutedrole|Sets the muted role.|`+setmutedrole <@role>`
Setwelcome|Sets the welcome message.|`+setwelcome <message>`

### Botowners

These commands may only be used by the owners of SauceBot.

Command | Description | Usage
---------------- | --------------| -------
Setgame|Changes the bot's game.|`+setgame <message>`

### Crime
Command | Description | Usage
---------------- | --------------| -------

### Gambling
Command | Description | Usage
---------------- | --------------| -------

### General
Command | Description | Usage
---------------- | --------------| -------
Modroles|View all mod roles in this server.|`+modroles`

### Moderation

These commands may only be used by a user with the set mod role with a permission level of 1 or the Administrator permission.

Command | Description | Usage
---------------- | --------------| -------
Ban|Swing the ban hammer on any member.|`+ban <@user> [reason]`
Clear|Remove up to 100 messages in the channel you type this command in.|`+clear <quantity> [reason]`
Kick|Kick any member.|`+kick <@member> [reason]`
Mute|Mute any member.|`+mute <@member> [# of hours] [reason]`
Unban|Lift the ban hammer on any member.|`+unban <user> [reason]`
Unmute|Unmute any member.|`+unmute <@member> [reason]`
Warn|Warn a misbehaving member|`+warn <@member> [reason]`

### Owners

These commands may only be used by a user with the set mod role with a permission level of 3 or the ownership of the server.

Command | Description | Usage
---------------- | --------------| -------
Addmodrole|Add a mod role.|`+addmodrole <@role> <permissionLevel>`
Removemodrole|Remove a mod role.|`+removemodrole <@role>`
Reset|Resets all user data in your server.|`+reset`
Resetuser|Reset any member's data.|`+resetuser [@member]`

### Sponsor
Command | Description | Usage
---------------- | --------------| -------
Buysponsor|Gain access to all the sponsorship benfits.|`+buysponsor [number of days]`
Claim|Claim a reward for being referred.|`+claim <code>`
Codeinfo|View the information of any referral code.|`+codeinfo <code>`
Pointsleaderboards|View the best referrers.|`+pointsleaderboards`
Refer|View your referral code along with an invite link to this server.|`+refer`
Sellpoints|View your referral code along with an invite link to this server.|`+sellpoints <number of points> <price> <@member>`
Setreferralcode|Set your referral code.|`+setreferralcode <code>`
Sponsor|View all the sponsorship benefits.|`+sponsor`
Sponsortime|View the time remaining on your sponsorship.|`+sponsortime [@member]`

### System
Command | Description | Usage
---------------- | --------------| -------
Help|All command information.|`+help [command]`
Invite|Click the link to invite SauceBot to your server!|`+invite`
Support|Ping support staff, and pin message.|`+support <message>`

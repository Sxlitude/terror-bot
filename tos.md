## terror discord bot terms of use

### What is this bot?
This discord bot has a security system that protects your discord server from nukes. Basically the bot allows only the owner and the trusted people of the guild to do actions on any channel, member, role or guild.

### Data Collection
This bot does not collect any sensitive information. The stuff it collects are just user IDs for security purpose. we always store your data privately. You can easily delete your data without requesting a deletion from us, by simply running the specific commands. everything is explained in detail below.

#### Why does it collect User IDs?
This bot contains three commands that are dependent on user IDs. these are `whitelist`, `unwhitelist` & `list`. though `unwhitelist` removes your data from our storage. The commands `whitelist` and `list` collect user IDs and displays them as it is stored, respectively. 

#### What do you mean by 'security purposes'?
This bot, when an event is fired, checks if the *executor* is *whitelisted*/*owner*/*client itself* or not. the reason of 'security purpose' is that, if the bot does not collect User IDs then it will act violently to any executor except owner & itself, causing harm to your server and your server admins as they may get banned.

#### How does this bot store my data?
The function of the bot is simple, it collects data like GuildID, OwnerID (& UserIDs only through `whitelist` command) only when a specific event is triggered. for instance, it collects Guild & Owner ID only when the bot is added to the guild. Similarly, it collects user ID when you add someone to whitelisted admins' list.
#### How can I remove my data from your bot?
there are multiple ways of doing so. The easiest way is to kick the bot from your server, because once the bot leaves a server it deletes all its data to save storage resources. Another way can be that, you can simply disable the antinuke by the command `;antinuke disable`. The thing this command does is just it deletes all the guild data and doesn't respond to any guild event if triggered unless the antinuke is turned back on.

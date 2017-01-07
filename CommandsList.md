Commands avaible with JeustoBot 
=========

X specifies a number  
Arguments between ( ) are optional


User
----
 
|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!commands |  | give a link to the commands |
|!help |  | return a link to get started with plug.dj |
|!eta | (@user) | show how long you have to wait before you reach the booth |
|!autowoot |  | return a link to RCS, the advised script/plugin to use for autowooting
|!rcs |  | return a link to RCS | 
|!ba |  | explain the Brand Ambassador rank | 
|!adblock |  | return a link to download Adblock | 
|!dclookup / !dc | (@user) | do dclookup for user | 
|!join |  | join the roulette if it's up | 
|!leave |  | leave the roulette if you joined |
|!google | tag | search the article on google |
|!weather | city | post the weather in the specified location |
|!urban | term | post the urban dictionary term |
|!emoji |  | return a link to a list with emoji's |
|!cookie | @user | give a cookie to user | 
|!kitkat | @user | give a kitkat to user | 
|!gif | (tag) | return a gif related to the tag provided, random gif if no tags are provided | 
|!ping |  | pong! | 
|!thor |  | users get moved to position 1 in the waitlist if they're worthy of Thor's hammer |
|!8ball | question | ask the bot a question, the bot will return random variations of a yes or no answer |
|!mood | @user | discover user's current mood |
|!dice |  | throw a dice |
|!randomnumber |  | give a random number between 1 and 100 | 
|!randomanimal |  | give a random animal name | 
|!randomcolor |  | give a random color | 
|!randomcorporation |  | give a random corporation name in the fortune 500 list  | 
|!randomcountry |  | give a random country | 
|!randomword |  | give a random common word | 
|!plugsupport |  | return a link to plug.dj support page |
|!plugba |  | return a link to plug.dj brand ambassador page |
|!plughelp |  | return a link to plug.dj help page |
|!plugcontact |  | return a link to plug.dj contact page |
|!plugtech |  | return a link to plug.dj tech  page |
|!plugblog |  | return a link to plug.dj blog page |
|!plugevents |  | return a link to plug.dj events page |
|!plugsubscriber |  | return a link to plug.dj subscription page |

DJ Resident
----
 
|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!english | @user | ask user to speak english (asked in the language they set plug to) | 
|!link |  | give a link to the current song | 
|!whois | @user | returns plug.dj related information about user |
|!getid | @user | get user’s plug.dj ID |
|!profile | @user | return a link to user’s plug.dj profile |
|!hello |  | say hello to JeustoBot |
|!bye |  | say goodbye to JeustoBot | 

Bouncer
----
 
|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!lockskip |  | skips, locks and moves the dj back up |
|!skippos | X | set the position to which skip and lockskip moves the dj |
|!forceskip |  | forceskip the current song | 
|!skipreason1 | X | remind a specific skip reason | 
|!rule1 | X | remind a specific rule |
|!kick | @user + (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!mute | @user + (X) | mute user, for X minutes if X is specified, otherwise for an undefined period|
|!unmute | @user | unmute user | 
|!ban | @user | bans user for 1 day | 
|!unban | @user | unban user | 
|!add | @user | add user to the waitlist |
|!move | @user | moves user to position X on the waitlist, default is position 1 | 
|!remove | @user | remove user from the waitlist |
|!filter |  | toggle the chat filter |
|!timeguard |  | toggle the timeguard |
|!maxlength | X | set the maximum length a song can be when timeguard is enabled |
|!motd | (message) + (X) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message | 
|!autoskip |  | skip songs automatically when they're done (use when the circles-bug happens) |  
|!version |  | return the current version of JeustoBot |
|!status |  | display JeustoBot's status and some settings |
|!test |  | check if the bot is alive
|!twitter |  | give a link to JeustoBot’s twitter profile |
|!owner |  | give some informations about JeustoBot’s owner |
|!jointime | @user | shows how long the user has been in the room |
|!afktime | @user | shows how long user has been afk |
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!sessionstats |  | display stats for the current session |
|!voteratio | @user | display the vote statistic for a user |
|!roulette |  | start a roulette |
|!spin | @user | move a user somewhere in the waitlist randomly | 
|!swap | @user1 + @user2 | swap the 2 users position in the waitlist | 
|!infocycle |  | give some informations about !cycle command |
|!infoafkremoval |  | give some informations about !afkremoval command |
|!infosongstats |  | give some informations about !songstats command |
|!infowelcome |  | give some informations about !welcome command |
|!infoautodisable |  | give some informations about !autodisable command |
|!infocommanddeletion |  | give some informations about !commanddeletion command |
|!infocycleguard |  | give some informations about !cycleguard command |
|!infofilter |  | give some informations about !filter command |
|!infotimeguard |  | give some informations about !timeguard command |
|!infolockguard |  | give some informations about !lockguard command |
|!inforestriceta |  | give some informations about !restricteta command |
|!infovoteskip |  | give some informations about !voteskip command |
|!infousercommands |  | give some informations about !usercommands command |
|!infolottery |  | give some informations about !lottery command | 

Manager
----
 
|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!lock |  | lock the waitlist |
|!unlock |  | unlock the waitlist |
|!clearchat |  | clear the chat |
|!deletechat | @user | delete all the chat messages by a certain user |
|!lockdown |  | lock down the room: only staff can chat |
|!cycle |  | toggle DJ cycle | 
|!afkremoval |  | toggle the afk check |
|!afklimit | X | sets the maximum afk time |
|!songstats |  | toggle song statistics | 
|!welcome |  | toggle the welcome message | 
|!autodisable |  | toggle the auto disable | 
|!commanddeletion |  | toggle if bot commands gets deleted | 
|!cycleguard |  | toggles the cycleguard |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled 
|!lockguard |  | toggle the lockguard | 
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
|!restricteta |  | toggle the restriction on eta: grey users can use it once an hour | 
|!voteskip |  | toggle the voteskip |
|!setvoteskip | X | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit |
|!usercommands |  | toggle user commands | 
|!setusercommands |  | set the cooldown on commands by grey users | 
|!lottery |  | toggle lottery | 
|!lotterytimer | X | set the time to wait before next lottery | 
|!kill |  | shut down JeustoBot |
|!destroy |  | destroy JeustoBot |
|!say | (message) | make JeustoBot say anything you want |







